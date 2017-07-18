# drupal-console-en

## Usage

Drupal Console project it's installed per each Drupal 8 website with English language by default.

To install Drupal Console package in other languages check the packages available at [https://packagist.org](https://packagist.org)


### Install Drupal Console

To install the appropriate version of Drupal Console project for your drupal installation, run the following composer command

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Install Drupal Console launcher

Drupal Console launcher was created to avoid conflicts between major and minor releases. Drupal Console binary commands are available to every Drupal 8 instance on the machine.
 
To install Drupal Console launcher globally follow the instruction below. 

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Contribute

Follow these steps to contribute to the current translation:

- Fork this repository via link [https://github.com/hechoendrupal/drupal-console-en#fork-destination-box](https://github.com/hechoendrupal/drupal-console-en#fork-destination-box)
- Clone your forked repostory to your local machine.
- Set up upstream

To receive the latest repository updates you must connect your fork to the main repository using the following git command

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-en.git
```

To fetch the latest contribution before to start, you must run the next commands

```
$ git fetch upstream
$ git merge upstream/master
```

N.B: Push your changes to your forked repository in order to create PR per day to avoid any conflicts with other contributors.
