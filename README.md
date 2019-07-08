# Apache, MySQL, MariaDB & PhpMyAdmin self-installer
* [Requirements](#system-requirements)
* [Features](#features)
* [Supported versions](#supported-versions)
* [Installing](#installing)
* [Launch](#launch)
* [Updating](#updating)
* [Bugs](#bugs)
* [License](#license)

# Requirements

* Unix-like OS

* curl

# Features 
* Automatically install all prerequisites
* Choice of PHP modules
* Install latest stable versions of MariaDB, PhpMyAdmin and Apache
* The user can install only apache 

# Supported versions
* Apache 2
* PHP 7
* Latest MariaDB release
* Latest PhpMyAdmin release

# Installing
* **curl** is required to download the script.

* If you are logged in as root 
```bash
curl https://uploads.admlbs.fr/download.php?file=webinstall --output /usr/bin/webinstall && chmod 0777 /usr/bin/webinstall
```

* If it's not the case : 

```bash
sudo curl https://uploads.admlbs.fr/download.php?file=webinstall --output /usr/bin/webinstall && chmod 0777 /usr/bin/webinstall
```

# Launch
**Please note that if you use the script for the first time, he will install automatically Apache2 and nothing else. In order to install MariaDB or PhpMyAdmin just restart the script using webinstall command.**
* To launch the script and install your webserver you must use sudo or being root

```bash
webinstall
```

* To see all commands please type 

```bash
sudo webinstall
```

# Bugs


* Please report all bugs to adam@admlbs.fr

# License

This programm is distribued under GNU General Public License v3.0


