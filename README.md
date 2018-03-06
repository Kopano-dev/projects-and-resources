# Kopano Community Projects and Resources

The goal of this repository is to provide an overview of third party projects in relation to Kopano. Everyone is welcome to get involved by creating listings for their projects, suggest new categories, or otherwise participating to this repository. If you would like to contribute, please make sure to review the [contribution guidelines](CONTRIBUTING.md).

## Table of contents

- [Antivirus Helpers](#antivirus-helpers)
- [Anti Spam Helpers](#anti-spam-integrations)
- [Client integrations](#client-integrations)
- [Data integrations](#data-integrations)
- [Distributions integrating Kopano](#distributions-integrating-kopano)
- [Migration Helpers](#migration-helpers)
- [Monitoring](#monitoring)
- [User Management](#user-Management)

- [Kopano dAgent/Spooler Plugins](#kopano-dagentspooler-plugins)
- Kopano WebApp
  - [Plugins/Integrations](#pluginsintegrations-1)
  - [Themes](#themes)
- Other
  - [Howtos and Guides](#howtos-and-guides)

### Antivirus Helpers

- [kopano-scan-attachments](https://github.com/bkram/kopano-scan-attachments) - Scan user stores for attachments with ClamAV and if required removing and replacing the attachment when infected. `GPL-2.0`

### Anti Spam Integrations

- [inotify-spamlearn](https://github.com/bkram/inotify-spamlearn) - A companion to the Kopano Core kopano-spamd, which is included from Kopano Core 8.6 new, this tool can handle the actual spam and ham processing. `GPL-3.0`

### Client integrations

- [Z-Push](https://wiki.z-hub.io/display/ZP) - Integrates mobile devices into Kopano through the ActiveSync protocol. [Source Code](https://stash.z-hub.io/projects/ZP/repos/z-push/) `AGPLv3` `stable`

### Data integrations

- [Kopano2JIRA](https://confluence.soenke-martens.de/display/PROJ/Kopano+to+Atlassian+JIRA+Adressbook+Sync) - Synchronizes all contacts of a Kopano folder one way to JIRA contact issues. [Source Code](https://bitbucket.soenke-martens.de/projects/JD/repos/kopano2jira/browse) `unkown license` `experimental`

### Distributions integrating Kopano

- [ClearOS](https://www.clearos.com/products/purchase/clearos-marketplace-apps/server/Kopano_Basic) - Install and manage Kopano on your ClearOS server. `unknown-license` `stable`
- [Kopano4UCS](https://wiki.z-hub.io/display/K4U/Kopano4UCS+Home) - Install and manage Kopano through the Univention Management Console. [Demo](https://www.univention.com/products/univention-app-center/app-catalog/kopano-core/), [Source Code](https://stash.z-hub.io/projects/K4U/repos/kopano4ucs/browse) `AGPLv3` `stable`

### Migration Helpers

- [egroupware2zarafa](https://github.com/bytemine/egroupware2zarafa) - Some scripts to export egroupware contacts and calendar data so it can be imported into Outlook/Zarafa. [Source Code](https://github.com/bytemine/egroupware2zarafa) `unknown license` `stable`

### Monitoring

- [Nagios4Kopano](https://exchange.nagios.org/directory/Plugins/Email-and-Groupware/Others/Nagios4Kopano/details) - This nagios plugin allows you to monitor your Kopano server by using the command kopano-stats --system. `GPL` `stable`

### User Management

- [LDAP Account Manager](https://www.ldap-account-manager.org/) - LAM Pro manages various account types in an LDAP directory. Kopano users, contacts, groups, dynamic groups and servers are supported.

### Kopano dAgent/Spooler Plugins

#### Plugins/Integrations

- [Kopano-dagent RewriteGALAddressesToSMTP](https://notabug.org/hp/kopano-dagent-rewritegaladdresses) - This plugin prevents dagent from changing recipient headers in emails on delivery. If you use aliases this allows you to see what alias a message was sent to. [Source Code](//notabug.org/hp/kopano-dagent-rewritegaladdresses) `AGPL-3.0+` `stable`

### Kopano WebApp

#### Plugins/Integrations

- [Calendar Importer and Exporter](https://git.sprinternet.at/zarafa_webapp/calendarimporter) - This plugin for the Zarafa Webapp provides a ICAL calendar importer. [Source Code](https://git.sprinternet.at/zarafa_webapp/calendarimporter) `unknown license` `stable`
- [Contact Importer and Exporter](https://git.sprinternet.at/zarafa_webapp/contactimporter) - The contact importer plugin for the Zarafa WebApp. [Source Code](https://git.sprinternet.at/zarafa_webapp/contactimporter) `unknown license` `stable`
- [Google2FA](https://community.zarafa.com/pg/plugins/project/32087/developer/norman/) - WebApp two-factor authentication with Google Authenticator. [Source Code](https://bitbucket.org/normanth/google2fa) `unkown license` `stable`
- [Gravatar](https://github.com/flok99/zarafa_gravatar) - Show a Gravatar avatar when no photo is set in the contacts. [Source Code](https://github.com/flok99/zarafa_gravatar) `GPL-2.0` `stable`
- [Switch Editor](https://github.com/MartyJustice/switcheditor) - Plugin for Kopano WebApp to switch between the HTML and plain text editor within an email. [Source Code](https://github.com/MartyJustice/switcheditor) `AGPLv3` `stable`
- [WebApp Fetchmail](https://github.com/olia-dev/kopano-webapp-fetchmail/releases) - Plugin that integrates Fetchmail into the Kopano WebApp. [Source Code](https://github.com/olia-dev/kopano-webapp-fetchmail) `AGPL-3.0` `stable`
- [WebApp IMAP Import](https://github.com/oxilion/zarafa-webapp-plugin-imapsync) - Plugin for Zarafa WebApp for importing IMAP accounts. [Source Code](https://github.com/oxilion/zarafa-webapp-plugin-imapsync) `AGPL-3.0` `stable`
- [WebApp Passwd](https://github.com/silentsakky/zarafa-webapp-passwd) - Plugin to add functionality of changing of password from Zarafa WebApp. [Source Code](https://github.com/silentsakky/zarafa-webapp-passwd) `AGPLv3` `stable`
- [WebApp privacyIDEA](https://github.com/bytemine/webapp-privacyidea) - Zarafa WebApp plugin to integrate 2FA with privacyIDEA. [Source Code](https://github.com/bytemine/webapp-privacyidea) `AGPLv3` `stable`

#### Themes

### Howtos and Guides

- [Kopano – der „neue“ Stern am Groupwarehimmel](https://www.pc-howto.com/kopano-der-neue-stern-am-groupwarehimmel-teil-1/) - German article series explaining the Kopano base installation.
