advancedblockmod
================

PHPBB3 Advanced Block Mod

Description:
Advanced Block MOD improves the blocking features of phpBB.

Features:
- Replaces too much simple, not finished and unmaintained check_dnsbl phpBB3 core feature.
- Adds more IP-RBL DNS, HTTP and Domain-RBL DNS blacklists and UTC-12 trick to phpBB3.
- Supported HTTP blacklists: Stop Forum Spam, BotScout, Akismet, Project Honey Pot, Block Disposable Email Adresses.
- All features and blacklists can be managed from extra ACP pages. Only some not important settings for the HTTP blacklists are hardcoded.
- Blacklists can be weighted from 0 to 5. The weight values are added to reach a threshold value of 5 before spam will been blocked. So if configured spam needs to been found on several blacklists before it is blocked.
- Adds a new log for Block actions. Adds logging for email_check_mx.
- Adds a feature to re-check posts and users for spam to the Forum logs, WHO IS ONLINE, MCP -> post details, MCP -> report details and ACP -> Manage users -> Overview.
- Allows to report spammers to HTTP blacklists manually and automatically.
- Adds a feature to require an e-mail address for guest postings. The e-mail address will been displayed only for administrators at the re-check spam pages.
- Supports Contact Board Administration MOD http://www.phpbb.com/customise/db/mod/c ... istration/ to redirect false positives to the contact page.
- Supports Advanced Double Activation Pack MOD http://www.phpbb.com/customise/db/mod/a ... tion_pack/ to add the Re-check spam feature to the ACP Verify user page.
- Supports Handyman` MOD version check - https://www.phpbb.com/customise/db/mod/ ... sion_check

Original Author: Martin Truckenbrodt

TODO:
- Add whitelisting feature
- CIDR country block feature
- Add ACL for spam report button
