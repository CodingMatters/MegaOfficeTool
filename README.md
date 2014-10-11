Mega Mitch Credit, Inc. Office Tool (MOT)
==============

MOT is an enterprise (internal) application used by [Mega Mitch Credit, Inc](http://www.megamitch.com) developed using [Zend Framework 2](http://framework.zend.com/).

[![Latest Stable Version](https://poser.pugx.org/megamitch/megamitch-office-tool/v/stable.svg)](https://packagist.org/packages/megamitch/megamitch-office-tool) [![Total Downloads](https://poser.pugx.org/megamitch/megamitch-office-tool/downloads.svg)](https://packagist.org/packages/megamitch/megamitch-office-tool) [![Latest Unstable Version](https://poser.pugx.org/megamitch/megamitch-office-tool/v/unstable.svg)](https://packagist.org/packages/megamitch/megamitch-office-tool) [![License](https://poser.pugx.org/megamitch/megamitch-office-tool/license.svg)](https://packagist.org/packages/megamitch/megamitch-office-tool) [![Build Status](https://travis-ci.org/megamitch/MegaOfficeTool.svg)](https://travis-ci.org/megamitch/MegaOfficeTool)

Installation
------------

Using Composer (recommended)
----------------------------
The recommended way to get a working copy of this project is to clone the repository
and use `composer` to install dependencies using the `create-project` command:

    curl -s https://getcomposer.org/installer | php --
    php composer.phar create-project --prefer-source --no-dev codingmatters/megamitch-mot path/to/install

Alternately, clone the repository and manually invoke `composer` using the shipped
`composer.phar`:

    cd my/project/dir
    git clone git://github.com/CodingMatters/MegaOfficeTool.git
    cd MegaOfficeTool
    git submodule init
    git submodue update
    php composer.phar self-update
    php composer.phar install

(The `self-update` directive is to ensure you have an up-to-date `composer.phar`
available.)
