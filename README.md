This is a Varying Vagrant Vagrants Dashboard for the excellent [Varying Vagrant Vagrants](https://github.com/Varying-Vagrant-Vagrants/VVV)

Its purpose is to dynamically load host links to all sites created in the VVV www path.

It also suggests the wonderful add-on bash script [VVV Site Wizard](https://github.com/aliso/vvv-site-wizard) for creating new sites.

[![Gitter Chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/topdown/VVV-Dashboard?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Instructions
-
Clone this repo to your VVV/www/default/ directory (`git clone https://github.com/topdown/VVV-Dashboard.git dashboard`)

Copy the dashboard-custom.php to VVV/www/default/dashboard-custom.php

---
### UPDATE Instructions 
From your dashboard directory ```git pull```

You no longer need to copy the style.css anywhere.

Delete the old VVV/www/default/dashboard-custom.php and copy the new version to VVV/www/default/dashboard-custom.php

Now move your dashboard directory so it is inside VVV/www/default/

As of 11/19/2015 there is a cache system, If don't see cache files on first dashboard load make sure dashboard/cache/ is writable. (It should be)

---

With Vagrant Up you should be able browse to your vagrant root www usually [vvv](http://vvv) or [vvv.dev](http://vvv.dev) and see the new dashboard.

** NEW: There are bound keys for the search feature, the enter key and down arrow key search down the list and the up arrow searches up.**


![image](https://raw.githubusercontent.com/topdown/VVV-Dashboard/master/screenshots/screenshot.png)

![image](https://raw.githubusercontent.com/topdown/VVV-Dashboard/master/screenshots/live-search.gif)

** More Screenshots**

[New Buttons](https://raw.githubusercontent.com/topdown/VVV-Dashboard/master/screenshots/host-list.png)

[Quick Server Info](https://raw.githubusercontent.com/topdown/VVV-Dashboard/master/screenshots/server-info.png)

[Theme List](https://raw.githubusercontent.com/topdown/VVV-Dashboard/master/screenshots/theme-list.png)

[Plugin List](https://raw.githubusercontent.com/topdown/VVV-Dashboard/master/screenshots/plugin-list.png)


---
** NOTE: ** This Dashboard project has no affiliation with Varying Vagrant Vagrants or any other components listed here.

---

### Change Log

---
11/22/15  version: 0.1.1

* Bug fixes for path issues


---
11/22/15  version: 0.1.0

* Added DB Backups to the dashboard


---
11/20/15  version: 0.0.9

* Added version check for VVV Dashboard
* Version check notice if a new version is available
* Display the last 10 PHP errors

---
11/20/15  version: 0.0.8

* Added update capabilities for plugins and themes
* Add mailcatcher menu item props: @atimmer topdown/VVV-Dashboard/pull/9

---
11/20/15  version: 0.0.7

* Added a scan depth setting
* Added purge forms for each of the cached systems
* Started cleaning up the index and moving HTML to views
* Added the ability for people to create custom.css to override our styles
* Added version constant to static files


---
11/19/2015 version: 0.0.6

* Added a simple Cache System to improve performance when collecting data
* Added get_plugins feature which will collect the plugins info from a selected installed site
* Added get_themes feature which will collect the themes info from a selected installed site
* Added quick server info to the sidebar
* Show/Hide sidebar
* Cookies for sidebar state (7 day cookie)
* Added some defined constants to the dashboard-custom.php (which means updating you need to replace the old)
* Added more screenshots
* Moved screenshots
* Updated Readme

---
5/18/2015  version: 0.0.5

* Added VV Command table
* Changed host list to responsive tables
* Changed host search to a live search

---
5/17/2015

* created develop branch

---
5/16/2015  version: 0.0.4

* Refactored getHosts function to also check if WP_DEBUG is true in each host
* Added it to the host list.
* Added host count
* Updated Screenshot
* Made the main view port wider moving commands to the sidebar
* Support for none WordPress sites

---
5/15/2015

* Update bower components
* Added jQuery
* Added Search Hosts feature
* Added max-height with automated scroll
* Updated install instruction and ReadMe
* Updated Screenshot

---

---

### ToDo's

---

* Maybe some wiki docs since this is getting a little bigger
* Fuzzy search for plugins and themes ? not sure yetRemove
* Do a count and maybe a list of DB backups for each host
* Refactor time, clean up some code and remove redundancy
* Dropdown Menu for tools but not Bootstrap it should be CSS only


