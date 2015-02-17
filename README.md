Mega Mitch Credit, Inc. Office Tool (MOT)
==============

MOT is an enterprise (internal) application used by [Mega Mitch Credit, Inc](http://www.megamitch.com) developed using [Zend Framework 2](http://framework.zend.com/).

[![Latest Stable Version](https://poser.pugx.org/megamitch/office-tool/v/stable.svg)](https://packagist.org/packages/megamitch/office-tool) [![Total Downloads](https://poser.pugx.org/megamitch/office-tool/downloads.svg)](https://packagist.org/packages/megamitch/office-tool) [![Latest Unstable Version](https://poser.pugx.org/megamitch/office-tool/v/unstable.svg)](https://packagist.org/packages/megamitch/office-tool) [![License](https://poser.pugx.org/megamitch/office-tool/license.svg)](https://packagist.org/packages/megamitch/office-tool) [![Build Status](https://travis-ci.org/megamitch/MegaOfficeTool.svg)](https://travis-ci.org/megamitch/MegaOfficeTool)

Submodules
----------

#### [Mot](https://github.com/megamitch/MOT_Application) [![Latest Stable Version](https://poser.pugx.org/megamitch/mot-application/v/stable.svg)](https://packagist.org/packages/megamitch/mot-application) [![License](https://poser.pugx.org/megamitch/mot-application/license.svg)](https://packagist.org/packages/megamitch/mot-application) [![Build Status](https://travis-ci.org/megamitch/MOT_Application.svg)](https://travis-ci.org/megamitch/MOT_Application) 

Mega Mitch Office Tool (MOT) is an internal application used for day-to-day transaction within Mega Mitch and its clients.

#### [MotUsers](https://github.com/megamitch/MOT_Users) [![Latest Stable Version](https://poser.pugx.org/megamitch/mot-users/v/stable.svg)](https://packagist.org/packages/megamitch/mot-users) [![License](https://poser.pugx.org/megamitch/mot-users/license.svg)](https://packagist.org/packages/megamitch/mot-users) [![Build Status](https://travis-ci.org/megamitch/MOT_Users.svg)](https://travis-ci.org/megamitch/MOT_Users) 

User management module.

#### [MotReports] (https://github.com/megamitch/MOT_Reports) [![Latest Stable Version](https://poser.pugx.org/megamitch/mot-reports/v/stable.svg)](https://packagist.org/packages/megamitch/mot-reports) [![License](https://poser.pugx.org/megamitch/mot-reports/license.svg)](https://packagist.org/packages/megamitch/mot-reports) [![Build Status](https://travis-ci.org/megamitch/MOT_Reports.svg)](https://travis-ci.org/megamitch/MOT_Reports)

Reporting module

#### [MotAttendance] (https://github.com/megamitch/Attendance) [![Latest Stable Version](https://poser.pugx.org/megamitch/mot-attendance/v/stable.svg)](https://packagist.org/packages/megamitch/mot-attendance) [![License](https://poser.pugx.org/megamitch/mot-attendance/license.svg)](https://packagist.org/packages/megamitch/mot-attendance) [![Build Status](https://travis-ci.org/megamitch/Attendance.svg)](https://travis-ci.org/megamitch/Attendance)

Daily transaction report for Mega Mitch Credit, Inc. employees

#### [MotOb] (https://github.com/megamitch/MOT_OB) [![Latest Stable Version](https://poser.pugx.org/megamitch/mot-ob/v/stable.svg)](https://packagist.org/packages/megamitch/mot-ob) [![License](https://poser.pugx.org/megamitch/mot-ob/license.svg)](https://packagist.org/packages/megamitch/mot-ob) [![Build Status](https://travis-ci.org/megamitch/MOT_OB.svg)](https://travis-ci.org/megamitch/MOT_OB)

Official Business tool for Mega Mitch, Inc. employees


Installation
------------

Using Composer (recommended)
----------------------------
The recommended way to get a working copy of this project is to clone the repository
and use `composer` to install dependencies using the `create-project` command:

    curl -s https://getcomposer.org/installer | php --
    sudo php composer.phar create-project --prefer-source --no-dev megamitch/office-tool /var/www/html/MOT

Alternately, clone the repository and manually invoke `composer` using the shipped
`composer.phar`:

    cd /var/www/html
    sudo git clone git://github.com/CodingMatters/MegaOfficeTool.git MOT
    cd MOT
    git submodule init
    git submodue update
    php composer.phar self-update
    php composer.phar install

(The `self-update` directive is to ensure you have an up-to-date `composer.phar`
available.)
