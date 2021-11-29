
# Installing

## Install patternlab with composer
**in Folder:**
web/themes/custom/avonis/patternlab
### Install dependencies

    $ composer install

## Install dependencies from package.json:
**in Folder:**
drupal/themes/custom/avonis

**run npm:**

    $ npm install

### Compiling
**in Folder:**
drupal/themes/custom/avonis

**run-development**:

    $ npm run build

**run-development-watcher**:

    $ npm run build:watch

**run-production**:

    $ npm run build:prod


# Compiling
**in Folder:**
web/themes/custom/avonis

###### Generate Pattern Lab

    $ php patternlab/core/console --generate

###### Start a server to view Pattern Lab

    $ php patternlab/core/console --server

