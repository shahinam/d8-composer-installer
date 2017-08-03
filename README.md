# Drupal Composer Installer

Composer based Drupal installer for Drupal 7 and 8.

## Usage

The versioning is as per Drupal, to grab latest version
```
composer create-project shahinam/drupal-installer:7.x-dev MY_PROJECT
composer create-project shahinam/drupal-installer:8.x-dev MY_PROJECT
```

Or grab a tagged version
```
composer create-project shahinam/drupal-installer:8.3 MY_PROJECT
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
