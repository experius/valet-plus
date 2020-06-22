## 2.0.0 (2020-02-28)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/2.0.0)

*  Added Github issue templates *(Lou van der Laarse)*
*  Add azure-pipelines.yml file for azure CI/CD integration (#394) *(Lou van der Laarse)*
*  Remove PR triggers from azure-pipeline configuration *(Lou van der Laarse)*
*   Add PHP_CodeSniffer and PSR-2 as project dependency (#399) *(Lou van der Laarse)*
*  Fix APCU_BC pecl extension generating errors upon install (#401) *(Lou van der Laarse)*
*  Add ioncube for php 7.3 (#402) *(Lou van der Laarse)*
*  Add zlib to devtools (#403) *(Lou van der Laarse)*
*  Add initial contributor guidelines documents (#404) *(Lou van der Laarse)*
*  Update to latest Magerun versions (#414) *(Bartek Igielski)*
*  Update Slack invite link *(Sam Granger)*
*  Remove dependency on mysql-utilities formula (v2.x) (#437) *(Martin Meredith)*
*  Add PHP 7.4 switch support(#425) *(Martin Meredith)*
*  Fix valet fix installing 7.1 instead of 7.2 (as per Readme) (#426) *(Martin Meredith)*
*  Fix Logic for detecting installation errors (#435) *(Martin Meredith)*
*  Always suffix Elasticsearch version in datapath #407 (#408) *(Mischa Braam)*
*  Fix PHP 7.4 not installing correct geoip version (#440) *(Martin Meredith)*
*  Fix PHP 7.0 installing wrong xdebug PECL extension version (#449) *(Lou van der Laarse)*
*  Fix MySQL not being linked upon install (#447) *(Lou van der Laarse)*
*  Add new PR template (#450) *(Lou van der Laarse)*
*  Bump version to 2.0.0 *(Lou van der Laarse)*
*  Remove major part of the readme.md *(Lou van der Laarse)*
*  Bump changelog to 2.0.0 *(Lou van der Laarse)*
*  Update PULL_REQUEST_TEMPLATE.md with correct format *(Lou van der Laarse)*
*  Update readme.md *(Frank Houtappels)*
*  Update readme.md *(Frank Houtappels)*
*  Update readme.md *(Frank Houtappels)*
*  Update readme.md *(Frank Houtappels)*
*  Fix Elasticsearch NGINX stub (#464) *(Sam Granger)*
*  Update readme.md *(Mischa Braam)*
*  Moved contributors to their own section. *(Sander)*


## 1.0.29 (2019-08-14)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.29)

*  Fix Shopware5 Driver to be updater compatible (#378) *(Steffen)*
*  Add  support for elasticsearch 6.8 (#371) *(Moritz Naczenski)*
*  Add ElasticSearch 6.8 support. (#372) *(Wesley Peeters)*
*  Load server environment variables for static files (#385) *(Winston Nolan)*
*  Fix Elasticsearch switch/install (#390) *(Mischa Braam)*
*  Bump version *(Mischa Braam)*


## 1.0.28 (2019-06-12)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.28)

*  Only write the z-performance.ini if it doesn't exist yet (#332) *(Julian)*
*  Read userpath from current user instead of file owner (#333) *(Koos van Egmond)*
*  Update mailhog and elasticsearch conf on domain change (#336) (#337) *(Julian)*
*  Update secure.valet.conf (#342) *(Jeremy Pry)*
*  Added memcache install / uninstall commands through brew and pecl. (#345) *(Sander)*
*  [TASK] Secure Domain Longer FastGCI timeout for local development (#346) *(Derrick Heesbeen)*
*  [TASK] Updated magerun2 to latest version to work with 2.3.1 (#347) *(Derrick Heesbeen)*
*  Add Shopware Platform Support (#355) *(Moritz Naczenski)*
*  Fix setting domain on install *(Mischa Braam)*
*  Add support to switch Elasticsearch version (#367) *(Mischa Braam)*
*  Bump version *(Sam Granger)*


## 1.0.27 (2019-03-19)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.27)

*  Update Wordpress to WordPress (#319) *(Jonathan Wold)*
*  Longer FastGCI timeout for local development (#326) *(Gabriel Somoza)*
*  Fix nginx SERVER_NAME being empty (#325) *(Gabriel Somoza)*
*  Add valet start with php switch (#324) *(Mischa Braam)*
*  Only show the paths if accessing from same machine (#313) *(Marco Silva)*
*  Remove --with-http2 option since it is now included in the base package (fixes #314) (#315) *(Laura Folco)*
*  Update version *(Sam Granger)*


## 1.0.26 (2019-01-25)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.26)

*  No force https to support share on ssl (#288) (#299) *(Mischa Braam)*
*  Add support for JSON:API in Drupal *(Sam Granger)*
*  Remove Gitter in favour of Slack *(Sam Granger)*
*  Change php install command *(Sam Granger)*
*  [DOCS] Added instructions how to add aliases for the current domain (#304) *(Mr. Lewis)*
*  Change instructions to include full Brew command (#306) *(Leland Clemmons)*
*  fix for local valet drivers *(samgranger)*
*  Update version *(Sam Granger)*


## 1.0.25 (2019-01-17)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.25)

*  Fixed typo: mailhog.conf -> elasticsearch.conf (#290) *(Marc)*
*  Upgrade n98-magerun2 to 3.0.3 (#291) *(Marc)*
*  Update KirbyValetDriver.php for Kirby CMS v3 (#297) *(Jonathan Muth)*
*  PHP 5.6 and 7.0 EOL changes (#302) *(Lou van der Laarse)*
*  Fix constant issue and not checking the tap of brew (#303) *(Kalin Stanchev)*
*  Fixed version no. mismatch (#289) *(Marc)*
*  Valet+ update *(Sam Granger)*
*  Update readme *(Sam Granger)*


## 1.0.24 (2018-12-20)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.24)

*  Fixed missing 404 overview of available sites. (#267) *(Sander)*
*  Add PHP 7.3 formulae and rename the 7.2 brew version (#272) *(Rok Vetršek)*
*  Update readme to use php7.2 (#250) *(Jose Cerrejon)*
*  Add rewrite feature (#278) *(Mischa Braam)*
*  Fixes issue with incorrect extensions path on non-default php versions. (#282) *(Peter van Westen)*


## 1.0.23 (2018-11-06)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.23)

*  Fix typo for mysql log *(Sam Granger)*
*  Bump version for next release *(Sam Granger)*
*  Fix switch from PHP 5.6 with constants *(Mischa Braam)*


## 1.0.22 (2018-11-04)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.22)

*  dynamically load drivers (#237) *(Arne)*
*  New logo *(Mischa Braam)*
*  Set constants for PHP brewnames to easily handle default and non-default PHP versions (#258) *(Luuk Schakenraad)*
*  Remove duplicate "Craft" and alphabetize (#256) *(Chris Rowe)*
*  Added the logs command to view logs (#261) *(Michiel Gerritsen)*
*  Add ‘logs’ feature to readme *(Mischa Braam)*
*  Check if the .my.cnf file exists and throw an warning if it does (#260) *(Michiel Gerritsen)*
*  Fix typo *(Mischa Braam)*


## 1.0.21 (2018-08-16)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.21)

*  Bump version (should of been in release) *(Sam Granger)*
*  Add slack channel to readme *(Mischa Braam)*
*  Implement AbstractService on Redis, Varnish & RabbitMq *(Mischa Braam)*
*  Open the current project in the logged in user’s browser *(Mischa Braam)*
*  Use user() instead *(Mischa Braam)*
*  Add ability to change db root password *(Mischa Braam)*
*  Prevent wrong password in config *(Mischa Braam)*
*  Double check binary path *(Mischa Braam)*
*  1.0.21 *(Mischa Braam)*


## 1.0.20 (2018-08-10)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.20)

*  Add author *(Sam Granger)*
*  Fix markdown syntax *(Sam Granger)*
*  Upgrade n98-magerun2 to 2.2.0 (#226) *(Marc)*
*  Change valet binary detection *(Mischa Braam)*
*  Add AbstractService to enable/disable a service, implemented on Mailhog *(Mischa Braam)*
*  Fix phpDoc *(Mischa Braam)*


## 1.0.19 (2018-07-14)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.19)

*  PHP.ini location (#206) *(Viktor Bijlenga)*
*  Add support for MFTF MagentoCLI commands (#220) *(Dave Macaulay)*
*   Added command to open current git project in SourceTree. (#222) *(Sander)*
*  Serve M2 js-translation.json in production mode (#223) *(Vinai Kopp)*
*  Add a remove action to the subdomain command (#210) *(Rok Vetršek)*
*  Improve formatting (#211) *(Bramus!)*
*  Revert "Allow use of symphony/process v4 (#188)" *(Sam Granger)*
*  Added support for proxying with nginx instead of using a Valet Driver. (#212) *(Thomas Krause)*
*  Allow configurable server environment variables *(Sam Granger)*
*  Wordpress multisite subdirectory driver. (#146) *(Wojtczyk)*
*  [refactoring][cleanup] Mysql Cli (#91) *(Salah Alkhwlani)*
*  Add $_SERVER[SERVER_NAME] to Magento 2 Driver *(samgranger)*
*  Change new mysql references to 5.7 *(samgranger)*
*  realpath change *(samgranger)*
*  Preparing 1.0.19 release *(samgranger)*
*  Unlink before linking PHP to prevent issues *(samgranger)*


## 1.0.18 (2018-06-21)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.18)

*  Adding Lou as author *(Sam Granger)*
*  Fixed opening a folder in PhpStorm + removed the need for git in the folder. (#195) *(Sander)*
*  pin mysql to 5.7 (#198) *(asdfx)*
*  Allow use of symphony/process v4 (#188) *(David de Boer)*
*  Bump version to 1.0.18 *(Sam Granger)*


## 1.0.17 (2018-06-11)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.17)

*  Add PECL fix command to check if pear configuration matches brew pear configuration (#173) *(Lou van der Laarse)*
*  Fix brew throwing a warning when switching to a non-installed php 7.2 version (#175) *(Lou van der Laarse)*
*  [cleanup] Duplicate memory limit & Whitespace removed (#178) *(Valentin)*
*  Introduce PECL enabled states (#184) *(Lou van der Laarse)*
*  Update version to 1.0.17 *(Sam Granger)*


## 1.0.16 (2018-05-22)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.16)

*  version no. should follow latest tag (#167) *(Marc)*
*  Update version to 1.0.16 *(Sam Granger)*


## 1.0.15 (2018-05-14)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.15)

*  Add Pimcore 5 to readme *(Sam Granger)*
*  Fix PECL switching directories per PHP version (#154) *(Lou van der Laarse)*
*  bugfix: call getVersion() on $currentVersion (#156) *(Marc)*
*  set version no. = latest tag (#155) *(Marc)*
*  add Shopware Valet Driver (#161) *(Bjoern Herzke)*


## 1.0.14 (2018-04-23)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.14)

*  Add gitter badge to readme *(Sam Granger)*
*  Update gitter badge *(Sam Granger)*
*  Added Pimcore 5 Valet Driver (#151) *(Stefan H Singer)*


## 1.0.13 (2018-04-11)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.13)

*  Update driver list *(Sam Granger)*
*  Add support for Magento 2 error routes (#110) *(John Hughes)*
*  Fixed valet fix command only being able to run after install (#137) *(Lou van der Laarse)*
*  Fixed geoip not installing and devtools not uninstalling (#138) *(Lou van der Laarse)*
*  Fixed error messages being undescriptive in Pecl#replaceIniDefinition() (#140) *(Lou van der Laarse)*


## 1.0.12 (2018-04-10)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.12)

*  Update StatamicValetDriver.php (#111) *(Simon Hamp)*
*  Added drivers for Neos and TYPO3 (#100) *(Johann Zelger)*
*  Update CraftValetDriver.php (#104) *(Aaron Van Ruler)*
*  Turn off APCu for now. (#98) *(Sander)*
*  Update n98-magerun2 commands to config:store:set (#120) *(Aidan Threadgold)*
*  Added multi-site, autocomplete and DOCUMENT_ROOT support to drupal driver (#128) *(Lou van der Laarse)*
*  Fixed valet domain not being set for valet services (#129) *(Lou van der Laarse)*
*  Fixed homebrew/php being deprecated in favor of homebrew/core (#130) *(Lou van der Laarse)*


## 1.0.11 (2017-12-27)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.11)

*  Added commands to enable/disable xdebug.remote_autostart. (#94) *(Sander)*


## 1.0.10 (2017-12-07)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.10)

*  Remove php restart if extension is already enabled. (#85) *(Sander)*
*  Stop and (re)start Dnsmasq service. (#83) *(Sander)*
*  Add PHP 7.2 support (#89) *(Dennis Fridrich)*
*  Change TLD from .dev to .test *(Sam Granger)*
*  1.0.10 *(Sam Granger)*


## 1.0.9 (2017-10-23)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.9)

*  Update my.cnf (#82) *(Robert Fridzema)*
*  Feature/defaults to questions (#84) *(Sander)*
*  Don’t cache js-translation.json for Magento 2 *(Tim Neutkens)*
*  1.0.9 *(Tim Neutkens)*


## 1.0.8 (2017-10-10)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.8)

*  Strip new timezone path in High Sierra. Fixes #80 *(Tim Neutkens)*
*  1.0.8 *(Tim Neutkens)*


## 1.0.7 (2017-10-10)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.7)

*  Upgrade php-intl to prevent breaking on version switch *(Tim Neutkens)*
*  Load custom drivers before returning cached driver *(Tim Neutkens)*
*  1.0.7 *(Tim Neutkens)*


## 1.0.6 (2017-10-05)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.6)

*  Lock tightenco/collect to the version supporting php 5.6 *(Tim Neutkens)*
*  1.0.6 *(Tim Neutkens)*


## 1.0.5 (2017-10-05)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.5)

*  Load LocalValetDriver before loading driver from cache *(Tim Neutkens)*
*  1.0.5 *(Tim Neutkens)*


## 1.0.4 (2017-09-22)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.4)

*  Add caching of Valet drivers *(Tim Neutkens)*
*  Add site path cache *(Tim Neutkens)*
*  Added gzip (un)compression when (re-)importing and exporting a db + m… (#62) *(SanderJP)*
*  Enable URL rewrite in Magento2 configure (#67) *(Barry vd. Heuvel)*
*  Add url rewrites for magento 2 docs *(Tim Neutkens)*
*  Document Elasticsearch versions (#69) *(Yngve Høiseth)*
*  Updated logging documentation *(Tim Neutkens)*
*  Lock silly-cli to 1.5.1 to keep support for PHP 5.6, Thanks @jmulleman! *(Tim Neutkens)*
*  1.0.4 *(Tim Neutkens)*


## 1.0.3 (2017-09-03)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.3)

*  added checks to verify USER and SUDO_USER exist befor returning them … (#57) *(Danny G Smith)*
*  Add missing semicolon. Fixes #59 *(Tim Neutkens)*
*  Add missing semicolons *(Tim Neutkens)*
*  Remove isset return *(Tim Neutkens)*
*  Run Magento2 compiler when ?profile is appended to the url *(Tim Neutkens)*
*  1.0.3 *(Tim Neutkens)*


## 1.0.2 (2017-08-27)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.2)

*  Avoid class conflict with Redis *(Tim Neutkens)*
*  1.0.2 *(Tim Neutkens)*


## 1.0.1 (2017-08-26)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.1)

*  Corrected typo. (#33) *(Taylor)*
*  [BUGFIX] Set quotation mark to correct place (#41) *(Jeroen Ketelaar)*
*  Provide clear documentation about relationship to Valet *(Tim Neutkens)*
*  Update Readme and licenses for better clarity on Valet relationship (#43) *(Matt Stauffer)*
*  Reduce apc.shm_size to fix apc_mmap error thrown by APCU. (#46) *(Armando Lüscher)*
*  Load service when installing *(Tim Neutkens)*
*  1.0.1 *(Tim Neutkens)*


## 1.0.0 (2017-08-09)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/1.0.0)

*  Remove unused functions *(Tim Neutkens)*
*  1.0.0 *(Tim Neutkens)*


## 0.5.8 (2017-08-08)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.5.8)

*  Add execute rights to bin/magento *(Tim Neutkens)*
*  Switch ioncube and xdebug phpstorm *(Tim Neutkens)*
*  Improve update instructions *(Tim Neutkens)*
*  Add libjpeg fix for php56 until brew fixes it *(Tim Neutkens)*
*  0.5.8 *(Tim Neutkens)*


## 0.5.7 (2017-08-07)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.5.7)

*  Enable LOAD DATA INFILE for MySQL *(Tim Neutkens)*
*  Move php-fpm log to `~/.valet/Log` *(Tim Neutkens)*
*  0.5.7 *(Tim Neutkens)*


## 0.5.6 (2017-08-04)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.5.6)

*  Add valet subdomain and valet subdomains *(Tim Neutkens)*
*  Document valet subdomains *(Tim Neutkens)*
*  0.5.6 *(Tim Neutkens)*


## 0.5.5 (2017-08-04)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.5.5)

*  Small improvement to the confirmation questions. (#30) *(SanderJP)*
*  Added isExtensionEnabled to check current status, fixed a bug where u… (#32) *(SanderJP)*
*  Updated list of available subcommands when using valet db (#31) *(SanderJP)*
*  Don’t use collect because of keys issue. Thanks @jerrylopez *(Tim Neutkens)*
*  Add mariadb support *(Tim Neutkens)*
*  Document mariadb support *(Tim Neutkens)*
*  0.5.5 *(Tim Neutkens)*


## 0.5.4 (2017-08-02)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.5.4)

*  Allow to start/restart/stop specific services *(Tim Neutkens)*
*  Check valet-plus repository for on-latest-version *(Tim Neutkens)*
*  0.5.4 *(Tim Neutkens)*


## 0.5.3 (2017-08-01)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.5.3)

*  Start elasticsearch after installation *(Tim Neutkens)*
*  Set application name to valet+ *(Tim Neutkens)*
*  0.5.3 *(Tim Neutkens)*


## 0.5.2 (2017-07-30)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.5.2)

*  Add confirmation question for database removal actions *(Tim Neutkens)*
*  0.5.2 *(Tim Neutkens)*


## 0.5.1 (2017-07-30)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.5.1)

*  Turn database and filename around for db export *(Tim Neutkens)*
*  0.5.1 *(Tim Neutkens)*


## 0.5.0 (2017-07-30)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.5.0)

*  Add clearer instructions for $PATH *(Tim Neutkens)*
*  Add ioncube enable/disable *(Tim Neutkens)*
*  Document ioncube support *(Tim Neutkens)*
*  Add valet db ls *(Tim Neutkens)*
*  Add timestamp to default db export *(Tim Neutkens)*
*  Add docs for db ls *(Tim Neutkens)*
*  0.5.0 *(Tim Neutkens)*


## 0.4.4 (2017-07-21)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.4.4)

*  Remove .sql suffix on db export *(Sam Granger)*
*  Only add .sql suffix if not provided in filename *(Sam Granger)*
*  0.4.4 *(Tim Neutkens)*


## 0.4.3 (2017-07-20)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.4.3)

*  Document custom ValetDriver *(Tim Neutkens)*
*  Provide the right upgrade instructions *(Tim Neutkens)*
*  0.4.3 *(Tim Neutkens)*


## 0.4.2 (2017-07-19)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.4.2)

*  Add valet configure for Magento 1 *(Tim Neutkens)*
*  Add valet db reimport and create db if it doesn’t exist when importing *(Tim Neutkens)*
*  0.4.2 *(Tim Neutkens)*


## 0.4.1 (2017-07-19)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.4.1)

*  Add composer installation instruction *(Tim Neutkens)*
*  valet configure support for env.php and config.php for Magento 2 *(Tim Neutkens)*
*  0.4.1 *(Tim Neutkens)*


## 0.4.0 (2017-07-13)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.4.0)

*  Flush Magento cache when using valet configure *(Tim Neutkens)*
*  0.4.0 *(Tim Neutkens)*


## 0.3.9 (2017-07-12)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.3.9)

*  Add release *(Tim Neutkens)*
*  Add release *(Tim Neutkens)*
*  0.3.9 *(Tim Neutkens)*


## 0.3.8 (2017-07-12)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.3.8)

*  0.3.8 *(Tim Neutkens)*


## 0.3.7 (2017-07-12)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.3.7)

*  Add release *(Tim Neutkens)*


## 0.3.6 (2017-07-12)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.3.6)

*  Alias magerun and magerun2 to their n98- version *(Tim Neutkens)*


## 0.3.5 (2017-07-12)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.3.5)

*  Add elasticsearch.dev *(Tim Neutkens)*


## 0.3.4 (2017-07-11)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.3.4)

*  Document log locations *(Tim Neutkens)*
*  Allow mailhog.dev *(Tim Neutkens)*


## 0.3.3 (2017-07-08)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.3.3)

*  Add page for when environment config is missing *(Tim Neutkens)*


## 0.3.2 (2017-07-08)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.3.2)

*  Fix Magento2 setup page *(Tim Neutkens)*


## 0.3.1 (2017-07-08)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.3.1)

*  Check gitDir and fall back to current dir *(Tim Neutkens)*


## 0.3.0 (2017-07-08)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.3.0)

*  Faster `valet use` *(Tim Neutkens)*


## 0.2.3 (2017-07-06)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.2.3)

*  added support to set machine timezone in config (#17) *(Daan Kouters)*
*  Let users install php 7 *(Tim Neutkens)*


## 0.2.2 (2017-07-05)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.2.2)

*  Install geoip php module *(Tim Neutkens)*


## 0.2.1 (2017-07-04)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.2.1)

*  Support php 7.2 *(Tim Neutkens)*


## 0.2.0 (2017-07-04)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.2.0)

*  Added missing $_SERVER variables for CakePHP 3 *(Steffen Brand)*
*  Improved HTTP_HOST rewriting *(Vic D'Elfant)*
*  Simplified HTTP_HOST rewriting *(Vic D'Elfant)*
*  Shortened isset() *(Vic D'Elfant)*
*  Add PHP72 to detectable PHP versions *(Korvin Szanto)*
*  Update PhpFpm.php *(Korvin Szanto)*
*  Fix issue with favicon 404s *(Adam Wathan)*
*  Ensure 128mb max client body size. *(Kim Ravn Hansen)*
*  Refactor to collections *(Adam Wathan)*
*  Run against nightly on Travis *(Adam Wathan)*


## 0.1.10 (2017-07-04)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.1.10)

*  Restart phpfpm after enabling xdebug *(Tim Neutkens)*


## 0.1.9 (2017-07-02)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.1.9)

*  Add automatic configuration for Magento 2 *(Tim Neutkens)*


## 0.1.8 (2017-06-30)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.1.8)

*  Add database drop and reset, also escape database name so you can have dashes in them *(Tim Neutkens)*
*  Add drop and reset docs *(Tim Neutkens)*


## 0.1.7 (2017-06-30)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.1.7)

*  Add exporting notice *(Tim Neutkens)*


## 0.1.6 (2017-06-30)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.1.6)

*  Add valet db export *(Tim Neutkens)*
*  Add documentation for valet db export *(Tim Neutkens)*


## 0.1.5 (2017-06-30)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.1.5)

*  Check the right taps *(Tim Neutkens)*


## 0.1.4 (2017-06-29)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.1.4)

*  Add license.md *(Tim Neutkens)*
*  Automatically start mailhog when installing *(Tim Neutkens)*


## 0.1.3 (2017-06-27)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.1.3)

*  Increase max execution time (#12) *(Jeroen Alewijns)*


## 0.1.2 (2017-06-22)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.1.2)

*  Add outline of features *(Tim Neutkens)*
*  Document user/pass *(Tim Neutkens)*
*  Better alignment of user/pass *(Tim Neutkens)*
*  Add support for providing database name *(Tim Neutkens)*


## 0.1.1 (2017-06-21)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.1.1)

*  Use new name *(Tim Neutkens)*


## 0.1.0 (2017-06-19)

[View Release](git@github.com:experius/valet-plus.git/commits/tag/0.1.0)

*  first *(Taylor Otwell)*
*  update composer json *(Taylor Otwell)*
*  tweak dnsmasq installation *(Taylor Otwell)*
*  remove dd *(Taylor Otwell)*
*  fix version *(Taylor Otwell)*
*  change messages *(Taylor Otwell)*
*  fix deps *(Taylor Otwell)*
*  increment version *(Taylor Otwell)*
*  update name *(Taylor Otwell)*
*  update files *(Taylor Otwell)*
*  create resolver directory if it doesnt exist *(Taylor Otwell)*
*  increment version *(Taylor Otwell)*
*  adding paths command *(Taylor Otwell)*
*  added prune command *(Taylor Otwell)*
*  adding commands *(Taylor Otwell)*
*  adding files *(Taylor Otwell)*
*  update version *(Taylor Otwell)*
*  fix restart *(Taylor Otwell)*
*  increment *(Taylor Otwell)*
*  general cleaning *(Taylor Otwell)*
*  share feature *(Taylor Otwell)*
*  tweak script detection *(Taylor Otwell)*
*  prompt for sudo within shell script itself *(Taylor Otwell)*
*  clean up chown *(Taylor Otwell)*
*  Fix bugs *(Taylor Otwell)*
*  check proto *(Taylor Otwell)*
*  fix up tunnel detection *(Taylor Otwell)*
*  rename file *(Taylor Otwell)*
*  sub prompt other commands *(Taylor Otwell)*
*  make link and unlink arguments optinoal *(Taylor Otwell)*
*  init log files if they dont exist *(Taylor Otwell)*
*  statamic support *(Taylor Otwell)*
*  determine php *(Taylor Otwell)*
*  remove path check *(Taylor Otwell)*
*  rename serve to park *(Taylor Otwell)*
*  added recall *(Taylor Otwell)*
*  rename recall to forget *(Taylor Otwell)*
*  silent output *(Taylor Otwell)*
*  increment version *(Taylor Otwell)*
*  fix *(Taylor Otwell)*
*  move server file *(Taylor Otwell)*
*  loosen requirementsS *(Taylor Otwell)*
*  dont override paths *(Taylor Otwell)*
*  increment version *(Taylor Otwell)*
*  working on readme *(Taylor Otwell)*
*  serving sites *(Taylor Otwell)*
*  docs *(Taylor Otwell)*
*  wip *(Taylor Otwell)*
*  wip *(Taylor Otwell)*
*  wip *(Taylor Otwell)*
*  adding links *(Taylor Otwell)*
*  sharing *(Taylor Otwell)*
*  docs *(Taylor Otwell)*
*  listing commands *(Taylor Otwell)*
*  docs *(Taylor Otwell)*
*  simplify *(Taylor Otwell)*
*  add note *(Taylor Otwell)*
*  note *(Taylor Otwell)*
*  break *(Taylor Otwell)*
*  note *(Taylor Otwell)*
*  note *(Taylor Otwell)*
*  note on supported frameworks *(Taylor Otwell)*
*  note *(Taylor Otwell)*
*  database *(Taylor Otwell)*
*  header *(Taylor Otwell)*
*  improve docs *(Taylor Otwell)*
*  note *(Taylor Otwell)*
*  working on docs *(Taylor Otwell)*
*  logs *(Taylor Otwell)*
*  swap to driver based setup *(Taylor Otwell)*
*  cleaning drivers *(Taylor Otwell)*
*  add files *(Taylor Otwell)*
*  prune on every command *(Taylor Otwell)*
*  comments *(Taylor Otwell)*
*  remove unneeded command *(Taylor Otwell)*
*  remove command *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  fix check *(Taylor Otwell)*
*  increment *(Taylor Otwell)*
*  cleanup *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Clarify share instructions slightly *(Adam Wathan)*
*  Remove "simply" and "just" from README. *(Jack McDade)*
*  Link dnsmasq and clarify some wording *(Matt Stauffer)*
*  fix conflicts *(Taylor Otwell)*
*  fix cons *(Taylor Otwell)*
*  docs on custom drivers *(Taylor Otwell)*
*  more documentation *(Taylor Otwell)*
*  move docs *(Taylor Otwell)*
*  update keywords *(Taylor Otwell)*
*  de-escalate sooner *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  fix statamic cp *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Fix missing bracket *(Jerguš Lejko)*
*  Add StaticValetDriver for static pages *(Jerguš Lejko)*
*  rewrite host on the fly for ngrok *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  improve static driver *(Taylor Otwell)*
*  tweak static driver *(Taylor Otwell)*
*  loosen requirements *(Taylor Otwell)*
*  tweaks to drivers. add jigsaw *(Taylor Otwell)*
*  tweak statamic sharing *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Add mime types for Handlebars / Mustache templates *(Jan Hohner)*
*  Add woff2 missing mime type *(Jerguš Lejko)*
*  wordpress driver *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  craft support *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  ValetDriver::serves() method should return bool *(Igor Pantović)*
*  Add Generic Driver to point to a public/ folder (SlimPHP, Non-Framework PHP) *(Joe Ferguson)*
*  Symfony2/3 Valet driver *(Igor Pantovic)*
*  Register SymfonyValetDriver within $drivers array *(Igor Pantovic)*
*  added which command for debugging *(Taylor Otwell)*
*  add files *(Taylor Otwell)*
*  Add Katana Driver *(Mohamed Said)*
*  Stop existing dnsmasq.conf from being obliterated *(Keoghan Litchfield)*
*  Quote all variables in shell script *(Jason P. Scharf)*
*  fixing statamic installer *(Taylor Otwell)*
*  fix wordpress permalinks *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  allow updating domain dynamically *(Taylor Otwell)*
*  a few fixes *(Taylor Otwell)*
*  tweaking thingsS *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Add Contao CMS driver *(Sebastian Schlein)*
*  fix undefined index in mimes array *(lifesign)*
*  change into front controller path when executing *(Taylor Otwell)*
*  Fix mine to mime *(Adam Wathan)*
*  some cleaning *(Taylor Otwell)*
*  Improve GenericPhpValetDriver, remove unnecessary check in WP driver *(Adam Wathan)*
*  Add Sculpin Valet driver *(Jason Walton)*
*  conslidate drivers into basic driver if possible *(Taylor Otwell)*
*  zonda *(Taylor Otwell)*
*  wordpress for later purposes *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  fixes *(Taylor Otwell)*
*  Remove '/Users/' prefix *(Pantelis Peslis)*
*  use caddy as the server into php *(Taylor Otwell)*
*  a few php fpm fixes *(Taylor Otwell)*
*  general code cleaning and refactoring *(Taylor Otwell)*
*  dont do logs by default *(Taylor Otwell)*
*  simplify user check *(Taylor Otwell)*
*  working on formatting *(Taylor Otwell)*
*  move caddy *(Taylor Otwell)*
*  update a few names *(Taylor Otwell)*
*  Tweak sed to work regardless of user/group values *(Adam Wathan)*
*  added brew class *(Taylor Otwell)*
*  cleaning restarts *(Taylor Otwell)*
*  chown caddyfile *(Taylor Otwell)*
*  fix chown *(Taylor Otwell)*
*  tweak caddyfile *(Taylor Otwell)*
*  Write a Caddy directory for loading additional configuration files. *(Taylor Otwell)*
*  always touch keep file *(Taylor Otwell)*
*  refactor a few functions *(Taylor Otwell)*
*  extract helper into autoloaded file *(Taylor Otwell)*
*  Dry's up things *(Kennedy Tedesco)*
*  BasicValetDriver - Minor change *(Kennedy Tedesco)*
*  progress refactoring *(Taylor Otwell)*
*  working on dnsmasq refactor *(Taylor Otwell)*
*  working on php fpm refactor *(Taylor Otwell)*
*  Check static folder for html file *(Jason Varga)*
*  Slash cleanup wasn't necessary *(Jason Varga)*
*  refactor and tests *(Taylor Otwell)*
*  add license file for caddy *(Taylor Otwell)*
*  add travis file *(Taylor Otwell)*
*  move files *(Taylor Otwell)*
*  skip check when testing *(Taylor Otwell)*
*  remove old php version from travis *(Taylor Otwell)*
*  add env variable *(Taylor Otwell)*
*  remove 5.5 *(Taylor Otwell)*
*  detect phpunit *(Taylor Otwell)*
*  fix tests user call *(Taylor Otwell)*
*  change to preg replace instead of sed *(Taylor Otwell)*
*  fix check *(Taylor Otwell)*
*  Fix docblocks *(Lucas Michot)*
*  version *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  allow php56 *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Escape file paths *(mattdfloyd)*
*  fix share *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  fix symlink storage on laravel driver *(Taylor Otwell)*
*  cleaning up code *(Taylor Otwell)*
*  Statamic V1 driver *(Jason Varga)*
*  Add Kirby CMS driver *(Pedro Borges)*
*  fix offset error in wp-admin *(Evan Mattson)*
*  added ngrok class *(Taylor Otwell)*
*  update readme *(Taylor Otwell)*
*  remove unneeded code. *(Taylor Otwell)*
*  Remove empty uri check and unnecessary condition *(Jason Varga)*
*  slight formatting *(Taylor Otwell)*
*  Fix filename *(Jason Varga)*
*  fix conflicts *(Taylor Otwell)*
*  fix a few things *(Taylor Otwell)*
*  fix conflicts *(Taylor Otwell)*
*  fixing conflicts *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Fix Caddyfile path *(Pantelis Peslis)*
*  cake driver *(Taylor Otwell)*
*  organize better *(Taylor Otwell)*
*  Create JoomlaValetDriver.php *(Christophor Wilson)*
*  Update require.php *(Christophor Wilson)*
*  Update ValetDriver.php *(Christophor Wilson)*
*  Move isActualFile() to ValetDriver *(Kennedy Tedesco)*
*  correcting a few script problems *(Taylor Otwell)*
*  tweaking scripts *(Taylor Otwell)*
*  tweaking scripts *(Taylor Otwell)*
*  adding note to update script *(Taylor Otwell)*
*  dont double sudo if already sudo *(Taylor Otwell)*
*  tweaks to scripts *(Taylor Otwell)*
*  keep user updated *(Taylor Otwell)*
*  remove character *(Taylor Otwell)*
*  move scripts *(Taylor Otwell)*
*  fix replacement *(Taylor Otwell)*
*  fix location *(Taylor Otwell)*
*  fix bug *(Taylor Otwell)*
*  fix autoload *(Taylor Otwell)*
*  link on every install *(Taylor Otwell)*
*  call back into source *(Taylor Otwell)*
*  call install on each update *(Taylor Otwell)*
*  added sudoers entries. *(Taylor Otwell)*
*  add files *(Taylor Otwell)*
*  move method to brew class *(Taylor Otwell)*
*  fix comment *(Taylor Otwell)*
*  Allows Valet to run under PHP 5.5 (#57) *(Glendon Solsberry)*
*  add Bedrock driver *(Evan Mattson)*
*  update driver location *(Evan Mattson)*
*  correct return value *(Evan Mattson)*
*  fix path *(Taylor Otwell)*
*  simplify dir checks *(Taylor Otwell)*
*  use variable *(Taylor Otwell)*
*  comment *(Taylor Otwell)*
*  remove variable *(Taylor Otwell)*
*  various fixes *(Taylor Otwell)*
*  increment verison *(Taylor Otwell)*
*  fix resolution *(Taylor Otwell)*
*  Fix resolution. *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Tweaking a few things. *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  extract logic *(Taylor Otwell)*
*  set descriptions *(Taylor Otwell)*
*  run commands as sudo *(Taylor Otwell)*
*  combine vars *(Taylor Otwell)*
*  load extensions *(Taylor Otwell)*
*  fix file paths on extensions *(Taylor Otwell)*
*  disable timeout *(Taylor Otwell)*
*  minor formatting *(Taylor Otwell)*
*  Add warning() helper (#58) *(Kennedy Tedesco)*
*  tweaks *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  tweak craft driver *(Taylor Otwell)*
*  fix env configs with craft *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Remove current-domain in favor of domain with no args (#61) *(Adam Wathan)*
*  remove else block *(Taylor Otwell)*
*  Consistency changes (#60) *(Daniel Morris)*
*  remove ide hint *(Taylor Otwell)*
*  Open website in your browser (#50) *(Robin Malfait)*
*  fix open for symlinks *(Taylor Otwell)*
*  shorten method *(Taylor Otwell)*
*  desc *(Taylor Otwell)*
*  add secure and unsecure *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  create sites directory *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  fix sites directory *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  fixed wrong spelling for the word "working" under the "which" command *(Rico Maglayon)*
*  Fix brew installations. *(Taylor Otwell)*
*  Fix tests. *(Taylor Otwell)*
*  Add some dotfiles (#73) *(Lucas Michot)*
*  Detect WordPress by configuration file (#65) *(Till Krüss)*
*  Fix spaces in path when using 'valet link' (#62) *(Jason P. Scharf)*
*  Remove useless imports (#76) *(Lucas Michot)*
*  Use assertFileExists and assertFileNotExists (#75) *(Lucas Michot)*
*  Use strict comparisons (#74) *(Lucas Michot)*
*  Populate SERVER_ADDR to avoid undefined index notices in WordPress (#77) *(Jan Pingel)*
*  Reducing conflicts with other libraries like illuminate/support by wrapping the tap method in a function_exists conditional. *(Nate Ritter)*
*  Revert "Reducing conflicts with other libraries like illuminate/support by wrapping the tap method in a function_exists conditional." *(Nate Ritter)*
*  Adding a function_exists conditional around the tap method to reduce conflict with the illuminate/support library *(Nate Ritter)*
*  fix scan certificates directory error when first change domain *(Gao Feng)*
*  update version *(Jerguš Lejko)*
*  Adds the option to view the Caddy access- and error-log using 'valet server-log' *(Jan Willem Kaper)*
*  Convert static file path extension to lowercase *(Steve Waag)*
*  ConfigurationTest updated with test_log_directory_is_created_with_log_files_if_it_doesnt_exist() function *(Jan Willem Kaper)*
*  Revert "ConfigurationTest updated with test_log_directory_is_created_with_log_files_if_it_doesnt_exist() function" *(Jan Willem Kaper)*
*  onfigurationTest updated with test_log_directory_is_created_with_log_files_if_it_doesnt_exist() functions (second attempt) *(Jan Willem Kaper)*
*  fix for the empty $name issue (#94) *(Vitaliy Ryepnoy)*
*  Added valet support for Symfony < 3.0 (#87) *(Philipp Bräutigam)*
*  Set DOCUMENT_ROOT when serving index.php files. *(Florian Schwaiger)*
*  Redirect wp-admin to wp-admin/ (#96) *(Thiery Laverdure)*
*  Drupal 7 & 8 Driver (#48) *(Tristan Payne)*
*  Add basic changes to alllow php71 *(Chris Brown)*
*  Update version *(Adam Wathan)*
*  Remove Composer-less functionality from master branch *(Adam Wathan)*
*  Fix bash error, update version *(Adam Wathan)*
*  Move Drupal driver *(Adam Wathan)*
*  Allow path parameter for valet park and forget *(Chris Brown)*
*  Add missing descriptions *(Chris Brown)*
*  Update version to match release *(Jason Conroy)*
*  Added option to pass custom parameters to ngrok *(René de Kat)*
*  Reword unsecure description *(Adam Wathan)*
*  Clean up log commands a bit *(Adam Wathan)*
*  Update version string *(Adam Wathan)*
*  Properly replace VALET_HOME_PATH in secure Caddy files *(Adam Wathan)*
*  Increment version *(Adam Wathan)*
*  Working on serving static files through Caddy instead of PHP *(Adam Wathan)*
*  Fix incorrect path replacement for server.php *(Adam Wathan)*
*  Start secure Caddyfiles from root and add dummy internal directive *(Adam Wathan)*
*  Use /dev/null as dummy internal folder *(Adam Wathan)*
*  Generate new Caddyfiles for secure sites on install *(Adam Wathan)*
*  Fix broken tests *(Adam Wathan)*
*  Remove mimes file *(Adam Wathan)*
*  Resecure TLS sites with configured domain, not dev *(Adam Wathan)*
*  Document slight hackiness of 'internal /dev/null' *(Adam Wathan)*
*  Support xip.io feature *(Levis Florian)*
*  Link to Laravel 5.3 Valet Docs. *(Syed Irfaq R. ⚡️)*
*  Test on PHP 7.1 *(Vincent Klaiber)*
*  Update Laravel docs link *(Vincent Klaiber)*
*  Stop running tests against 5.5 *(Adam Wathan)*
*  Fix conflict *(Adam Wathan)*
*  Update Taylors email *(Vincent Klaiber)*
*  Use sockets instead of port 9000 *(Korvin Szanto)*
*  Add composer cache to travis config *(Korvin Szanto)*
*  Update to Caddy 0.9.1 to support Sierra *(Adam Wathan)*
*  Update some brittle mocks 😩🔫 *(Adam Wathan)*
*  Don't run tests on 5.5 *(Adam Wathan)*
*  clean up grim code *(Taylor Otwell)*
*  wording *(Taylor Otwell)*
*  fix spacing *(Taylor Otwell)*
*  spacing *(Taylor Otwell)*
*  remove superstition *(Taylor Otwell)*
*  remove superstition *(Taylor Otwell)*
*  remove logs method *(Taylor Otwell)*
*  Update Caddy to 0.9.2 *(Adam Wathan)*
*  Revert to Caddy 0.9.1 *(Adam Wathan)*
*  Update version string *(Adam Wathan)*
*  Rewrite TLS Caddy files on install *(Adam Wathan)*
*  Update version *(Adam Wathan)*
*  Explicitly set PHP FPM port on install *(Adam Wathan)*
*  Update version *(Adam Wathan)*
*  Added Share Command to the List of Commands *(akoury)*
*  Redirect wp/wp-admin to wp/wp-admin/ *(Fredrik Forsmo)*
*  Revert to serving static files through PHP until Caddy bug resolved *(Adam Wathan)*
*  Use Caddy 0.9.1 *(Adam Wathan)*
*  Add test coverage for setting FPM socket *(Adam Wathan)*
*  Fix conflicts *(Adam Wathan)*
*  Fix changes according to @adamwathan request *(Levis Florian)*
*  Fix changes according to @adamwathan request *(Levis Florian)*
*  Set SERVER_NAME variable for WordPress driver *(Adam Wathan)*
*  Visibility keywords!! Gross. *(Adam Wathan)*
*  Move php-fpm socket *(Michael Gruschwitz)*
*  Update caddy stubs *(Michael Gruschwitz)*
*  Fix php-fpm socket location in caddy stubs *(Michael Gruschwitz)*
*  Update tests *(Michael Gruschwitz)*
*  Serve static files through Caddy instead of PHP *(Adam Wathan)*
*  Add test coverage for php.ini changes on install *(Adam Wathan)*
*  Use custom Caddy build until new version is tagged *(Adam Wathan)*
*  Use a separate .ini file instead of editing the main php.ini file *(Adam Wathan)*
*  Disable default_mimetype with ini_set instead of via config file *(Adam Wathan)*
*  Don't even set the INI setting because it doesn't work in 5.6, do this dumb hack instead. *(Adam Wathan)*
*  Explain this disgusting grue *(Adam Wathan)*
*  Update to Caddy 0.9.3 *(Adam Wathan)*
*  Remove dead code *(Adam Wathan)*
*  Remove mimes file *(Adam Wathan)*
*  Reference Caddy issue re: internal directive in stubs *(Adam Wathan)*
*  Update version string *(Adam Wathan)*
*  Fix issues with parse_url sometimes failing *(Adam Wathan)*
*  Adding function_exists to retry *(Daniel Polito)*
*  Allow homebrew to be installed in non-standard locations *(Adam Wathan)*
*  Revert to using port instead of socket to see if it helps stale page issue *(Adam Wathan)*
*  Remove .DS_Store file from Caddy directory when starting Caddy *(Keith Damiani)*
*  Support a SiteValetDriver in the site path *(Jason Varga)*
*  Run brew list as user *(Adam Lavin)*
*  Update brew list to use runAsUser instead of directly sudoing *(Adam Lavin)*
*  Update version string *(Adam Wathan)*
*  Send empty Content-Type header to force nginx to determine on it's own *(Adam Wathan)*
*  Add stub *(Adam Wathan)*
*  Grueing around *(Adam Wathan)*
*  Listen on port instead of socket *(Adam Wathan)*
*  Use socket, store in valet home and set loose permissions *(Adam Wathan)*
*  resolve real path *(Taylor Otwell)*
*  fix nginx support *(Taylor Otwell)*
*  working on tests *(Taylor Otwell)*
*  workin gon tests *(Taylor Otwell)*
*  fix another test *(Taylor Otwell)*
*  fix another test *(Taylor Otwell)*
*  fix another test *(Taylor Otwell)*
*  Remove grim array type hints *(Adam Wathan)*
*  Update version string *(Adam Wathan)*
*  Use assertContains instead of assertTrue + strpos *(Adam Wathan)*
*  Fix test to run under Linux CI *(Adam Wathan)*
*  Fix potential resolve() helper function conflict (#218) *(Caleb Porzio)*
*  Update ngrok to version 2.1.18 (#207) *(Will Vincent)*
*  Adds multi-locale support to the Craft CMS driver (#229) *(M. Mikkel Rummelhoff)*
*  Show proper Travis badge (#228) *(Daniel Polito)*
*  Add a concrete5 driver that provides the environment (#158) *(Korvin Szanto)*
*  version *(Taylor Otwell)*
*  Update readme.md *(Taylor Otwell)*
*  Update readme.md *(Taylor Otwell)*
*  Update readme.md *(Taylor Otwell)*
*  tweak command *(jerguslejko)*
*  fix broken change *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Set correct SCRIPT_FILENAME for HTTPS configurations *(Adam Wathan)*
*  Fix typo in docblock *(Michaël Lecerf)*
*  Use UUID for static asset path instead of "static" *(Adam Wathan)*
*  Also look for wp-config-sample when detecting WP *(Adam Wathan)*
*  Update version string *(Adam Wathan)*
*  Fix for query string in PHP (#259) *(Mark van Eijk)*
*  Add client_max_body_size to config (#253) *(Jürgen van Dijk)*
*  Fixes issue #244, where the Craft CMS admin panel is inaccessible (#252) *(M. Mikkel Rummelhoff)*
*  Upgrading PHP to 7.1 (#227) *(Daniel Polito)*
*  use local valet driver as name *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Fix for query string in secure config *(Alex Bouma)*
*  Fix large-upload problems by setting PHP limits and Nginx max size *(Chris Brown)*
*  Update minimum PHP requirement to 5.6 *(Chris Brown)*
*  Update readme.md *(Taylor Otwell)*
*  Update readme.md *(Taylor Otwell)*
*  Fix for issue #250 - brew package nginx-full not properly recognized as a valid nginx installation *(Pierre-Luc Brunet)*
*  Uses the correct service name if nginx-full is installed instead of nginx *(Pierre-Luc Brunet)*
*  Corrected left over "nginx" string left for stop command *(Pierre-Luc Brunet)*
*  Explicitly stop and start brew services instead of restart *(Adam Wathan)*
*  Fix test *(Adam Wathan)*
*  Add support for Craft 3 Beta *(Scott Wakefield)*
*  Make variable names consistent *(Scott Wakefield)*
*  Add ability to pass directory to `valet open` *(Than Tibbetts)*
*  Add the ability to switch between versions on PHP *(Eric Van Johnson)*
*  Address when users adds a decimal to the version. *(Eric Van Johnson)*
*  Lock phpunit version *(Cretu Eusebiu)*
*  add wildcard san certs *(Josh Manders)*
*  Dry's up PHP installation *(Kennedy Tedesco)*
*  pretty print sites *(Josh Manders)*
*  Making changes suggested by @adamwathan *(Eric Van Johnson)*
*  Show install, start, stop and restart log info *(Antonio Carlos Ribeiro)*
*  Fix issue where linked sites break parked sites *(Adam Wathan)*
*  Check nginx.conf for errors before restarting nginx *(Antonio Carlos Ribeiro)*
*  Formatting *(Adam Wathan)*
*  Remove sudoers entries *(Leon Jacobs)*
*  Fix issue when conf.d folder doesn't exist *(Adam Wathan)*
*  Bump version *(Adam Wathan)*
*  Formatting *(Adam Wathan)*
*  Use curly braces in string interpolation *(Adam Wathan)*
*  Capitalize PHP *(Adam Wathan)*
*  Forbid access to most commands if Valet is not installed *(Antonio Carlos Ribeiro)*
*  Forbid access to most commands if Valet is not installed *(Antonio Carlos Ribeiro)*
*  Filter out .conf files when creating secure URL list *(Josh Larson)*
*  Obliterate filthy typehints *(Adam Wathan)*
*  Add Magento2 driver *(Joe Constant)*
*  Add support for versions path in URLs added in Magento 2.1.3 *(Joe Constant)*
*  Fix contao driver never gets loaded *(Michael Gruschwitz)*
*  secure option for link *(Andrej Mihaliak)*
*  Add new Symfony directory structure in driver *(Mario Young)*
*  Show installed php versions when switching to non-existent version *(Tim Neutkens)*
*  PHP version switcher *(Tim Neutkens)*
*  Remove unused function *(Tim Neutkens)*
*  Restart php-fpm the right way *(Tim Neutkens)*
*  Added mysql *(Tim Neutkens)*
*  Stop as sudo *(Tim Neutkens)*
*  Add PHP extensions and ini for performance *(Tim Neutkens)*
*  Disable garabage collection based on blackfire report *(Tim Neutkens)*
*  Fix Mysql installation *(Tim Neutkens)*
*  Magento2 driver *(Tim Neutkens)*
*  Fix signed static urls *(Tim Neutkens)*
*  Stop session validation *(Tim Neutkens)*
*  Add valet db create and valet db open *(Tim Neutkens)*
*  Add maxfiles limit config file *(Tim Neutkens)*
*  Add devtools installation *(Tim Neutkens)*
*  Fix sub commands *(Tim Neutkens)*
*  Stop mysql *(Tim Neutkens)*
*  sudo stop mysql *(Tim Neutkens)*
*  Add node version manager *(Tim Neutkens)*
*  Start mysql as user *(Tim Neutkens)*
*  Run as user *(Tim Neutkens)*
*  Fix mysql crashes *(Tim Neutkens)*
*  Set permissions to 777 *(Tim Neutkens)*
*  Add support for valet db open . *(Tim Neutkens)*
*  Get git dirname instead of current dirname when available *(Tim Neutkens)*
*  Remove nvm *(Tim Neutkens)*
*  Fix static version sign in dev mode *(Tim Neutkens)*
*  Check for /static or /media *(Tim Neutkens)*
*  Add tcp_nopush and tcp_nodelay *(Tim Neutkens)*
*  Revert "Fix static version sign in dev mode" *(Tim Neutkens)*
*  Add redis + mysql import *(Tim Neutkens)*
*  Fix mysql has gone away. Thanks @samgranger *(Tim Neutkens)*
*  Prettier not found page *(Tim Neutkens)*
*  Escape domains *(Tim Neutkens)*
*  Add site naem to title tag *(Tim Neutkens)*
*  Clean up readme *(Tim Neutkens)*
*  Remove laravel from readme *(Tim Neutkens)*
*  Remove duplicate taps *(Tim Neutkens)*
*  Add documentation *(Tim Neutkens)*
*  Add link wrapper around here *(Tim Neutkens)*
*  Remove what valet+ provides *(Tim Neutkens)*
*  Naming *(Tim Neutkens)*
*  Add redis docs *(Tim Neutkens)*
*  Add table of contents *(Tim Neutkens)*
*  Remove created with doctoc *(Tim Neutkens)*
*  Add xdebug support *(Tim Neutkens)*
*  Unset server.php variables before passing it off to user code *(Tim Neutkens)*
*  Add xdebug documentation *(Tim Neutkens)*
*  Move intro to the right position *(Tim Neutkens)*
*  Improve Xdebug documentation *(Tim Neutkens)*
*  Add gittower and phpstorm support *(Tim Neutkens)*
*  Add vscode support, document phpstorm / tower support *(Tim Neutkens)*
*  Add mailhog support. Fixes #8 *(Tim Neutkens)*
*  Add valet ssh-key, fixes #9 *(Tim Neutkens)*
*  Cleanup readme *(Tim Neutkens)*
*  set sql mode *(siemen)*
*  Generate images using get.php magento *(Tim Neutkens)*
*  Remove sudo stop *(Tim Neutkens)*
*  Fix rootpassword *(Tim Neutkens)*
*  Pass right url to static version *(Tim Neutkens)*
*  Elasticsearch support *(Tim Neutkens)*
*  Add logo *(Tim Neutkens)*
*  Resize logo *(Tim Neutkens)*
*  Typo in elasticsearch description *(Tim Neutkens)*
*  Default to php7 instead of 7.1 *(Tim Neutkens)*
*  Fix start command *(Tim Neutkens)*


