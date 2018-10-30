[openbsd-br.org](http://www.openbsd-br.org)
-


This repository contains the source files of openbsd-br.org. If you want to colaborate, 
please fork it and submit a pull request.

**OpenBSD Brasil**

Wanna chat with us?

`irc.freenode.net` `#openbsd-br`


#### Configuring Website:

To install the website on your computer, you will need PHP and Composer. Composer will install some 
PHP dependencies to run the project.

`php -r "readfile('https://getcomposer.org/installer');" > composer-setup.php`

`php composer-setup.php`

`php -r "unlink('composer-setup.php');"`

`php composer.phar install`

`php -S localhost:8000`

Now, just open your browser and see the result at: http://localhost:8000



[![Deployment status from DeployBot](https://ggrigon.deploybot.com/badge/66802254090711/64144.svg)](http://deploybot.com)
