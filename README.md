# Drupal 8 Composer Installer

Composer based Drupal 8 installer.

## Usage
```
composer create-project shahinam/d8-composer-installer MY_PROJECT
```

## Basic composer usage
### Install a module
```
composer require drupal/<module-name>
```
Examples
```
composer require drupal/devel
composer require drupal/ctools
```

This will install latest available version. If you want to specify a version
```
composer require drupal/<module-name>:<version>
```

### Update a module
```
composer update drupal/<module-name>
```
