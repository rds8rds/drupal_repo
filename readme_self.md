these are the composer commands I need to use for letting composer know where to install dependecies

At project folder:

composer config vendor-dir vendor
composer config repositories.1 composer https://asset-packagist.org
composer config preferred-install dist

composer recommended projects:

composer require drush/drush:^10.0 --no-update
composer require drupal/stage_file_proxy --no-update
composer require drupal/mysql56 --no-update
composer require cweagans/composer-patches --no-update
