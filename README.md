NGINX 1.17-alpine, PHP 7.3, XDEBUG, MARIADB 10.5, +VSCODE Config
=================================================

# Config #

`docker-compose.yml` on the root of your project.
`config` containing nginx and php-fpm config for it.
`web` containing index.php for NGINX root directory.
`.vscode` containing VSCode config for XDEBUG.

You have to set your IP addr for XDEBUG.
`/config/php-fpm/xdebug-ini-overrides.ini`

# How to run #

`cd` to your project and run `docker-compose up -d`

NGINX: `localhost:80`

MySQL: **host:** `localhost`; **port:** `3306`

XDEBUG: **port:** `9001`






