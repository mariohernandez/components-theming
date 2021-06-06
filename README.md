# Component-based Theming
A hands-on training workshop by your friends at [Mediacurrent](https://mediacurrent.com).

This is a 4 hours training workshop to teach the basics of component-building and integration with Drupal 9.

## About this project

This is a DDEV-Local-based project.  You need to [Install Docker and DDEV-local](https://ddev.readthedocs.io/en/stable/#installation) before proceeding.

## Setup the project

1. Clone this repo `git clone git@github.com:mariohernandez/components-theming.git`

1. Navigate to new project: `cd components-theming`

1. Start up DDEV-local: `ddev start`

1. Download and Install Drupal Core and PHP Dependencies: `ddev composer install`

1. Run Drupal's install: `ddev drush site:install -y`

1. Import a working database: `ddev import-db --src=web/db.sql`

1. Start up Drupal: `ddev drush uli`
