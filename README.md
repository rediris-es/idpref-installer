# Introduction

This project is used to bootstrap a new IdP installation (or, in the future, update the IdP). 

The project aims to have all the needed dependencies correctly configured.

# Dependencies

The installation of IdP requires composer.

Composer can be downloaded running this command:

`curl -sS https://getcomposer.org/installer | php`

Finally, it can be configured globally to have the composer command in any directory on your computer.

`mv composer.phar /usr/local/bin/composer`

# Usage

In order to produce an initial installation, execute the following command:

`composer install`

In your current directory a simplesamlphp directory will be created with the initial configuration to run the IdP installer within.

In order to update all packages and dependencies up to the latest stable version, execute the following command:
 
`composer update`
