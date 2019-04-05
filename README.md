# Conferences

## Install dependencies

    composer install

## Filesystem permissions

    chmod 777 tmp translations

## Import initial configuration

    drush si minimal
    drush config-set "system.site" uuid "a693f4ca-caab-4f41-a85f-fb5979030586"
    drush cim
