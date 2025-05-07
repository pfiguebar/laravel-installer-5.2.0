1._ INSTALADOR LARAVEL
composer global require laravel/installer:5.2.0
laravel --version

2._ SHELL
nano ~/.bashrc
export PATH="$HOME/.config/composer/vendor/bin:$PATH"
source ~/.bashrc

3._ CREAR PROYECTO
laravel new laravel11-task

   _                               _
  | |                             | |
  | |     __ _ _ __ __ ___   _____| |
  | |    / _` | '__/ _` \ \ / / _ \ |
  | |___| (_| | | | (_| |\ V /  __/ |
  |______\__,_|_|  \__,_| \_/ \___|_|


 ┌ Would you like to install a starter kit? ────────────────────┐
 │ Laravel Breeze                                               │
 └──────────────────────────────────────────────────────────────┘

 ┌ Which Breeze stack would you like to install? ───────────────┐
 │ Livewire (Volt Class API) with Alpine                        │
 └──────────────────────────────────────────────────────────────┘

 ┌ Would you like dark mode support? ───────────────────────────┐
 │ Yes                                                          │
 └──────────────────────────────────────────────────────────────┘

 ┌ Which testing framework do you prefer? ──────────────────────┐
 │ Pest                                                         │
 └──────────────────────────────────────────────────────────────┘

 ┌ Would you like to initialize a Git repository? ──────────────┐
 │ No                                                           │
 └──────────────────────────────────────────────────────────────┘

Creating a "laravel/laravel" project at "./laravel11-task"
Installing laravel/laravel (v12.0.7)
  - Downloading laravel/laravel (v12.0.7)
  - Installing laravel/laravel (v12.0.7): Extracting archive
Created project in /home/usuario01/laravel11-task
> @php -r "file_exists('.env') || copy('.env.example', '.env');"
Loading composer repositories with package information
Updating dependencies
Lock file operations: 110 installs, 0 updates, 0 removals
  - Locking brick/math (0.12.3)
  - Locking carbonphp/carbon-doctrine-types (3.2.0)
  - Locking dflydev/dot-access-data (v3.0.3)
  - Locking doctrine/inflector (2.0.10)
  - Locking doctrine/lexer (3.0.1)
  - Locking dragonmantank/cron-expression (v3.4.0)
  - Locking egulias/email-validator (4.0.4)
  - Locking fakerphp/faker (v1.24.1)
  - Locking filp/whoops (2.18.0)
  - Locking fruitcake/php-cors (v1.3.0)
  - Locking graham-campbell/result-type (v1.1.3)
  - Locking guzzlehttp/guzzle (7.9.3)
  - Locking guzzlehttp/promises (2.2.0)
  - Locking guzzlehttp/psr7 (2.7.1)
  - Locking guzzlehttp/uri-template (v1.0.4)
  - Locking hamcrest/hamcrest-php (v2.1.1)
  - Locking laravel/framework (v12.12.0)
  - Locking laravel/pail (v1.2.2)
  - Locking laravel/pint (v1.22.0)
  - Locking laravel/prompts (v0.3.5)
  - Locking laravel/sail (v1.42.0)
  - Locking laravel/serializable-closure (v2.0.4)
  - Locking laravel/tinker (v2.10.1)
  - Locking league/commonmark (2.7.0)
  - Locking league/config (v1.2.0)
  - Locking league/flysystem (3.29.1)
  - Locking league/flysystem-local (3.29.0)
  - Locking league/mime-type-detection (1.16.0)
  - Locking league/uri (7.5.1)
  - Locking league/uri-interfaces (7.5.0)
  - Locking mockery/mockery (1.6.12)
  - Locking monolog/monolog (3.9.0)
  - Locking myclabs/deep-copy (1.13.1)
  - Locking nesbot/carbon (3.9.1)
  - Locking nette/schema (v1.3.2)
  - Locking nette/utils (v4.0.6)
  - Locking nikic/php-parser (v5.4.0)
  - Locking nunomaduro/collision (v8.8.0)
  - Locking nunomaduro/termwind (v2.3.0)
  - Locking phar-io/manifest (2.0.4)
  - Locking phar-io/version (3.2.1)
  - Locking phpoption/phpoption (1.9.3)
  - Locking phpunit/php-code-coverage (11.0.9)
  - Locking phpunit/php-file-iterator (5.1.0)
  - Locking phpunit/php-invoker (5.0.1)
  - Locking phpunit/php-text-template (4.0.1)
  - Locking phpunit/php-timer (7.0.1)
  - Locking phpunit/phpunit (11.5.19)
  - Locking psr/clock (1.0.0)
  - Locking psr/container (2.0.2)
  - Locking psr/event-dispatcher (1.0.0)
  - Locking psr/http-client (1.0.3)
  - Locking psr/http-factory (1.1.0)
  - Locking psr/http-message (2.0)
  - Locking psr/log (3.0.2)
  - Locking psr/simple-cache (3.0.0)
  - Locking psy/psysh (v0.12.8)
  - Locking ralouphie/getallheaders (3.0.3)
  - Locking ramsey/collection (2.1.1)
  - Locking ramsey/uuid (4.7.6)
  - Locking sebastian/cli-parser (3.0.2)
  - Locking sebastian/code-unit (3.0.3)
  - Locking sebastian/code-unit-reverse-lookup (4.0.1)
  - Locking sebastian/comparator (6.3.1)
  - Locking sebastian/complexity (4.0.1)
  - Locking sebastian/diff (6.0.2)
  - Locking sebastian/environment (7.2.0)
  - Locking sebastian/exporter (6.3.0)
  - Locking sebastian/global-state (7.0.2)
  - Locking sebastian/lines-of-code (3.0.1)
  - Locking sebastian/object-enumerator (6.0.1)
  - Locking sebastian/object-reflector (4.0.1)
  - Locking sebastian/recursion-context (6.0.2)
  - Locking sebastian/type (5.1.2)
  - Locking sebastian/version (5.0.2)
  - Locking staabm/side-effects-detector (1.0.5)
  - Locking symfony/clock (v7.2.0)
  - Locking symfony/console (v7.2.6)
  - Locking symfony/css-selector (v7.2.0)
  - Locking symfony/deprecation-contracts (v3.5.1)
  - Locking symfony/error-handler (v7.2.5)
  - Locking symfony/event-dispatcher (v7.2.0)
  - Locking symfony/event-dispatcher-contracts (v3.5.1)
  - Locking symfony/finder (v7.2.2)
  - Locking symfony/http-foundation (v7.2.6)
  - Locking symfony/http-kernel (v7.2.6)
  - Locking symfony/mailer (v7.2.6)
  - Locking symfony/mime (v7.2.6)
  - Locking symfony/polyfill-ctype (v1.32.0)
  - Locking symfony/polyfill-intl-grapheme (v1.32.0)
  - Locking symfony/polyfill-intl-idn (v1.32.0)
  - Locking symfony/polyfill-intl-normalizer (v1.32.0)
  - Locking symfony/polyfill-mbstring (v1.32.0)
  - Locking symfony/polyfill-php80 (v1.32.0)
  - Locking symfony/polyfill-php83 (v1.32.0)
  - Locking symfony/polyfill-uuid (v1.32.0)
  - Locking symfony/process (v7.2.5)
  - Locking symfony/routing (v7.2.3)
  - Locking symfony/service-contracts (v3.5.1)
  - Locking symfony/string (v7.2.6)
  - Locking symfony/translation (v7.2.6)
  - Locking symfony/translation-contracts (v3.5.1)
  - Locking symfony/uid (v7.2.0)
  - Locking symfony/var-dumper (v7.2.6)
  - Locking symfony/yaml (v7.2.6)
  - Locking theseer/tokenizer (1.2.3)
  - Locking tijsverkoyen/css-to-inline-styles (v2.3.0)
  - Locking vlucas/phpdotenv (v5.6.2)
  - Locking voku/portable-ascii (2.0.3)
  - Locking webmozart/assert (1.11.0)
Writing lock file
Installing dependencies from lock file (including require-dev)
Package operations: 110 installs, 0 updates, 0 removals
  - Downloading doctrine/lexer (3.0.1)
  - Downloading webmozart/assert (1.11.0)
  - Downloading dragonmantank/cron-expression (v3.4.0)
  - Downloading fakerphp/faker (v1.24.1)
  - Downloading symfony/polyfill-php83 (v1.32.0)
  - Downloading symfony/http-foundation (v7.2.6)
  - Downloading fruitcake/php-cors (v1.3.0)
  - Downloading psr/http-message (2.0)
  - Downloading psr/http-client (1.0.3)
  - Downloading ralouphie/getallheaders (3.0.3)
  - Downloading psr/http-factory (1.1.0)
  - Downloading guzzlehttp/psr7 (2.7.1)
  - Downloading guzzlehttp/promises (2.2.0)
  - Downloading guzzlehttp/guzzle (7.9.3)
  - Downloading guzzlehttp/uri-template (v1.0.4)
  - Downloading symfony/console (v7.2.6)
  - Downloading nunomaduro/termwind (v2.3.0)
  - Downloading phpoption/phpoption (1.9.3)
  - Downloading graham-campbell/result-type (v1.1.3)
  - Downloading vlucas/phpdotenv (v5.6.2)
  - Downloading symfony/css-selector (v7.2.0)
  - Downloading tijsverkoyen/css-to-inline-styles (v2.3.0)
  - Downloading symfony/var-dumper (v7.2.6)
  - Downloading symfony/polyfill-uuid (v1.32.0)
  - Downloading symfony/uid (v7.2.0)
  - Downloading symfony/routing (v7.2.3)
  - Downloading symfony/process (v7.2.5)
  - Downloading symfony/polyfill-intl-idn (v1.32.0)
  - Downloading symfony/mime (v7.2.6)
  - Downloading psr/event-dispatcher (1.0.0)
  - Downloading symfony/event-dispatcher-contracts (v3.5.1)
  - Downloading symfony/event-dispatcher (v7.2.0)
  - Downloading psr/log (3.0.2)
  - Downloading egulias/email-validator (4.0.4)
  - Downloading symfony/mailer (v7.2.6)
  - Downloading symfony/error-handler (v7.2.5)
  - Downloading symfony/http-kernel (v7.2.6)
  - Downloading symfony/finder (v7.2.2)
  - Downloading ramsey/collection (2.1.1)
  - Downloading brick/math (0.12.3)
  - Downloading ramsey/uuid (4.7.6)
  - Downloading symfony/translation (v7.2.6)
  - Downloading symfony/clock (v7.2.0)
  - Downloading nesbot/carbon (3.9.1)
  - Downloading monolog/monolog (3.9.0)
  - Downloading league/uri-interfaces (7.5.0)
  - Downloading league/uri (7.5.1)
  - Downloading league/mime-type-detection (1.16.0)
  - Downloading league/flysystem-local (3.29.0)
  - Downloading league/flysystem (3.29.1)
  - Downloading nette/utils (v4.0.6)
  - Downloading nette/schema (v1.3.2)
  - Downloading dflydev/dot-access-data (v3.0.3)
  - Downloading league/config (v1.2.0)
  - Downloading league/commonmark (2.7.0)
  - Downloading laravel/serializable-closure (v2.0.4)
  - Downloading laravel/prompts (v0.3.5)
  - Downloading laravel/framework (v12.12.0)
  - Downloading laravel/pail (v1.2.2)
  - Downloading laravel/pint (v1.22.0)
  - Downloading symfony/yaml (v7.2.6)
  - Downloading laravel/sail (v1.42.0)
  - Downloading nikic/php-parser (v5.4.0)
  - Downloading psy/psysh (v0.12.8)
  - Downloading laravel/tinker (v2.10.1)
  - Downloading hamcrest/hamcrest-php (v2.1.1)
  - Downloading mockery/mockery (1.6.12)
  - Downloading filp/whoops (2.18.0)
  - Downloading nunomaduro/collision (v8.8.0)
  - Downloading staabm/side-effects-detector (1.0.5)
  - Downloading sebastian/version (5.0.2)
  - Downloading sebastian/type (5.1.2)
  - Downloading sebastian/recursion-context (6.0.2)
  - Downloading sebastian/object-reflector (4.0.1)
  - Downloading sebastian/object-enumerator (6.0.1)
  - Downloading sebastian/global-state (7.0.2)
  - Downloading sebastian/exporter (6.3.0)
  - Downloading sebastian/environment (7.2.0)
  - Downloading sebastian/diff (6.0.2)
  - Downloading sebastian/comparator (6.3.1)
  - Downloading sebastian/code-unit (3.0.3)
  - Downloading sebastian/cli-parser (3.0.2)
  - Downloading phpunit/php-timer (7.0.1)
  - Downloading phpunit/php-text-template (4.0.1)
  - Downloading phpunit/php-invoker (5.0.1)
  - Downloading phpunit/php-file-iterator (5.1.0)
  - Downloading theseer/tokenizer (1.2.3)
  - Downloading sebastian/lines-of-code (3.0.1)
  - Downloading sebastian/complexity (4.0.1)
  - Downloading sebastian/code-unit-reverse-lookup (4.0.1)
  - Downloading phpunit/php-code-coverage (11.0.9)
  - Downloading phar-io/version (3.2.1)
  - Downloading phar-io/manifest (2.0.4)
  - Downloading myclabs/deep-copy (1.13.1)
  - Downloading phpunit/phpunit (11.5.19)
  - Installing doctrine/inflector (2.0.10): Extracting archive
  - Installing doctrine/lexer (3.0.1): Extracting archive
  - Installing symfony/polyfill-ctype (v1.32.0): Extracting archive
  - Installing webmozart/assert (1.11.0): Extracting archive
  - Installing dragonmantank/cron-expression (v3.4.0): Extracting archive
  - Installing symfony/deprecation-contracts (v3.5.1): Extracting archive
  - Installing psr/container (2.0.2): Extracting archive
  - Installing fakerphp/faker (v1.24.1): Extracting archive
  - Installing symfony/polyfill-php83 (v1.32.0): Extracting archive
  - Installing symfony/polyfill-mbstring (v1.32.0): Extracting archive
  - Installing symfony/http-foundation (v7.2.6): Extracting archive
  - Installing fruitcake/php-cors (v1.3.0): Extracting archive
  - Installing psr/http-message (2.0): Extracting archive
  - Installing psr/http-client (1.0.3): Extracting archive
  - Installing ralouphie/getallheaders (3.0.3): Extracting archive
  - Installing psr/http-factory (1.1.0): Extracting archive
  - Installing guzzlehttp/psr7 (2.7.1): Extracting archive
  - Installing guzzlehttp/promises (2.2.0): Extracting archive
  - Installing guzzlehttp/guzzle (7.9.3): Extracting archive
  - Installing symfony/polyfill-php80 (v1.32.0): Extracting archive
  - Installing guzzlehttp/uri-template (v1.0.4): Extracting archive
  - Installing symfony/polyfill-intl-normalizer (v1.32.0): Extracting archive
  - Installing symfony/polyfill-intl-grapheme (v1.32.0): Extracting archive
  - Installing symfony/string (v7.2.6): Extracting archive
  - Installing symfony/service-contracts (v3.5.1): Extracting archive
  - Installing symfony/console (v7.2.6): Extracting archive
  - Installing nunomaduro/termwind (v2.3.0): Extracting archive
  - Installing voku/portable-ascii (2.0.3): Extracting archive
  - Installing phpoption/phpoption (1.9.3): Extracting archive
  - Installing graham-campbell/result-type (v1.1.3): Extracting archive
  - Installing vlucas/phpdotenv (v5.6.2): Extracting archive
  - Installing symfony/css-selector (v7.2.0): Extracting archive
  - Installing tijsverkoyen/css-to-inline-styles (v2.3.0): Extracting archive
  - Installing symfony/var-dumper (v7.2.6): Extracting archive
  - Installing symfony/polyfill-uuid (v1.32.0): Extracting archive
  - Installing symfony/uid (v7.2.0): Extracting archive
  - Installing symfony/routing (v7.2.3): Extracting archive
  - Installing symfony/process (v7.2.5): Extracting archive
  - Installing symfony/polyfill-intl-idn (v1.32.0): Extracting archive
  - Installing symfony/mime (v7.2.6): Extracting archive
  - Installing psr/event-dispatcher (1.0.0): Extracting archive
  - Installing symfony/event-dispatcher-contracts (v3.5.1): Extracting archive
  - Installing symfony/event-dispatcher (v7.2.0): Extracting archive
  - Installing psr/log (3.0.2): Extracting archive
  - Installing egulias/email-validator (4.0.4): Extracting archive
  - Installing symfony/mailer (v7.2.6): Extracting archive
  - Installing symfony/error-handler (v7.2.5): Extracting archive
  - Installing symfony/http-kernel (v7.2.6): Extracting archive
  - Installing symfony/finder (v7.2.2): Extracting archive
  - Installing ramsey/collection (2.1.1): Extracting archive
  - Installing brick/math (0.12.3): Extracting archive
  - Installing ramsey/uuid (4.7.6): Extracting archive
  - Installing psr/simple-cache (3.0.0): Extracting archive
  - Installing symfony/translation-contracts (v3.5.1): Extracting archive
  - Installing symfony/translation (v7.2.6): Extracting archive
  - Installing psr/clock (1.0.0): Extracting archive
  - Installing symfony/clock (v7.2.0): Extracting archive
  - Installing carbonphp/carbon-doctrine-types (3.2.0): Extracting archive
  - Installing nesbot/carbon (3.9.1): Extracting archive
  - Installing monolog/monolog (3.9.0): Extracting archive
  - Installing league/uri-interfaces (7.5.0): Extracting archive
  - Installing league/uri (7.5.1): Extracting archive
  - Installing league/mime-type-detection (1.16.0): Extracting archive
  - Installing league/flysystem-local (3.29.0): Extracting archive
  - Installing league/flysystem (3.29.1): Extracting archive
  - Installing nette/utils (v4.0.6): Extracting archive
  - Installing nette/schema (v1.3.2): Extracting archive
  - Installing dflydev/dot-access-data (v3.0.3): Extracting archive
  - Installing league/config (v1.2.0): Extracting archive
  - Installing league/commonmark (2.7.0): Extracting archive
  - Installing laravel/serializable-closure (v2.0.4): Extracting archive
  - Installing laravel/prompts (v0.3.5): Extracting archive
  - Installing laravel/framework (v12.12.0): Extracting archive
  - Installing laravel/pail (v1.2.2): Extracting archive
  - Installing laravel/pint (v1.22.0): Extracting archive
  - Installing symfony/yaml (v7.2.6): Extracting archive
  - Installing laravel/sail (v1.42.0): Extracting archive
  - Installing nikic/php-parser (v5.4.0): Extracting archive
  - Installing psy/psysh (v0.12.8): Extracting archive
  - Installing laravel/tinker (v2.10.1): Extracting archive
  - Installing hamcrest/hamcrest-php (v2.1.1): Extracting archive
  - Installing mockery/mockery (1.6.12): Extracting archive
  - Installing filp/whoops (2.18.0): Extracting archive
  - Installing nunomaduro/collision (v8.8.0): Extracting archive
  - Installing staabm/side-effects-detector (1.0.5): Extracting archive
  - Installing sebastian/version (5.0.2): Extracting archive
  - Installing sebastian/type (5.1.2): Extracting archive
  - Installing sebastian/recursion-context (6.0.2): Extracting archive
  - Installing sebastian/object-reflector (4.0.1): Extracting archive
  - Installing sebastian/object-enumerator (6.0.1): Extracting archive
  - Installing sebastian/global-state (7.0.2): Extracting archive
  - Installing sebastian/exporter (6.3.0): Extracting archive
  - Installing sebastian/environment (7.2.0): Extracting archive
  - Installing sebastian/diff (6.0.2): Extracting archive
  - Installing sebastian/comparator (6.3.1): Extracting archive
  - Installing sebastian/code-unit (3.0.3): Extracting archive
  - Installing sebastian/cli-parser (3.0.2): Extracting archive
  - Installing phpunit/php-timer (7.0.1): Extracting archive
  - Installing phpunit/php-text-template (4.0.1): Extracting archive
  - Installing phpunit/php-invoker (5.0.1): Extracting archive
  - Installing phpunit/php-file-iterator (5.1.0): Extracting archive
  - Installing theseer/tokenizer (1.2.3): Extracting archive
  - Installing sebastian/lines-of-code (3.0.1): Extracting archive
  - Installing sebastian/complexity (4.0.1): Extracting archive
  - Installing sebastian/code-unit-reverse-lookup (4.0.1): Extracting archive
  - Installing phpunit/php-code-coverage (11.0.9): Extracting archive
  - Installing phar-io/version (3.2.1): Extracting archive
  - Installing phar-io/manifest (2.0.4): Extracting archive
  - Installing myclabs/deep-copy (1.13.1): Extracting archive
  - Installing phpunit/phpunit (11.5.19): Extracting archive
50 package suggestions were added by new dependencies, use `composer suggest` to see details.
Generating optimized autoload files
> Illuminate\Foundation\ComposerScripts::postAutoloadDump
> @php artisan package:discover --ansi

   INFO  Discovering packages.  

  laravel/pail ................................................................................................................................ DONE
  laravel/sail ................................................................................................................................ DONE
  laravel/tinker .............................................................................................................................. DONE
  nesbot/carbon ............................................................................................................................... DONE
  nunomaduro/collision ........................................................................................................................ DONE
  nunomaduro/termwind ......................................................................................................................... DONE

80 packages you are using are looking for funding.
Use the `composer fund` command to find out more!
> @php artisan vendor:publish --tag=laravel-assets --ansi --force

   INFO  No publishable resources for tag [laravel-assets].  

No security vulnerability advisories found
> @php artisan key:generate --ansi

   INFO  Application key set successfully.  

> @php -r "file_exists('database/database.sqlite') || touch('database/database.sqlite');"
> @php artisan migrate --graceful --ansi

   INFO  Preparing database.  

  Creating migration table ............................................................................................................. 8.56ms DONE

   INFO  Running migrations.  

  0001_01_01_000000_create_users_table ................................................................................................ 19.90ms DONE
  0001_01_01_000001_create_cache_table ................................................................................................. 7.18ms DONE
  0001_01_01_000002_create_jobs_table ................................................................................................. 17.01ms DONE

 ┌ Which database will your application use? ───────────────────┐
 │ MySQL                                                        │
 └──────────────────────────────────────────────────────────────┘

./composer.json has been updated
Running composer update laravel/breeze
Loading composer repositories with package information
Updating dependencies
Lock file operations: 1 install, 0 updates, 0 removals
  - Locking laravel/breeze (v2.3.6)
Writing lock file
Installing dependencies from lock file (including require-dev)
Package operations: 1 install, 0 updates, 0 removals
  - Downloading laravel/breeze (v2.3.6)
  - Installing laravel/breeze (v2.3.6): Extracting archive
Generating optimized autoload files
> Illuminate\Foundation\ComposerScripts::postAutoloadDump
> @php artisan package:discover --ansi

   INFO  Discovering packages.  

  laravel/breeze .............................................................................................................................. DONE
  laravel/pail ................................................................................................................................ DONE
  laravel/sail ................................................................................................................................ DONE
  laravel/tinker .............................................................................................................................. DONE
  nesbot/carbon ............................................................................................................................... DONE
  nunomaduro/collision ........................................................................................................................ DONE
  nunomaduro/termwind ......................................................................................................................... DONE

80 packages you are using are looking for funding.
Use the `composer fund` command to find out more!
> @php artisan vendor:publish --tag=laravel-assets --ansi --force

   INFO  No publishable resources for tag [laravel-assets].  

No security vulnerability advisories found
Using version ^2.3 for laravel/breeze
./composer.json has been updated
Running composer update livewire/livewire livewire/volt
Loading composer repositories with package information
Updating dependencies
Lock file operations: 2 installs, 0 updates, 0 removals
  - Locking livewire/livewire (v3.6.3)
  - Locking livewire/volt (v1.7.1)
Writing lock file
Installing dependencies from lock file (including require-dev)
Package operations: 2 installs, 0 updates, 0 removals
  - Downloading livewire/livewire (v3.6.3)
  - Downloading livewire/volt (v1.7.1)
 0/2 [>---------------------------]   0%
 1/2 [==============>-------------]  50%
 2/2 [============================] 100%
  - Installing livewire/livewire (v3.6.3): Extracting archive
  - Installing livewire/volt (v1.7.1): Extracting archive
 0/2 [>---------------------------]   0%
 2/2 [============================] 100%
Generating optimized autoload files
> Illuminate\Foundation\ComposerScripts::postAutoloadDump
> @php artisan package:discover --ansi

   INFO  Discovering packages.  

  laravel/breeze ........................................................ DONE
  laravel/pail .......................................................... DONE
  laravel/sail .......................................................... DONE
  laravel/tinker ........................................................ DONE
  livewire/livewire ..................................................... DONE
  livewire/volt ......................................................... DONE
  nesbot/carbon ......................................................... DONE
  nunomaduro/collision .................................................. DONE
  nunomaduro/termwind ................................................... DONE

81 packages you are using are looking for funding.
Use the `composer fund` command to find out more!
> @php artisan vendor:publish --tag=laravel-assets --ansi --force

   INFO  No publishable resources for tag [laravel-assets].  

No security vulnerability advisories found
./composer.json has been updated
Running composer update phpunit/phpunit
Loading composer repositories with package information
Updating dependencies
Lock file operations: 0 installs, 0 updates, 26 removals
  - Removing myclabs/deep-copy (1.13.1)
  - Removing phar-io/manifest (2.0.4)
  - Removing phar-io/version (3.2.1)
  - Removing phpunit/php-code-coverage (11.0.9)
  - Removing phpunit/php-file-iterator (5.1.0)
  - Removing phpunit/php-invoker (5.0.1)
  - Removing phpunit/php-text-template (4.0.1)
  - Removing phpunit/php-timer (7.0.1)
  - Removing phpunit/phpunit (11.5.19)
  - Removing sebastian/cli-parser (3.0.2)
  - Removing sebastian/code-unit (3.0.3)
  - Removing sebastian/code-unit-reverse-lookup (4.0.1)
  - Removing sebastian/comparator (6.3.1)
  - Removing sebastian/complexity (4.0.1)
  - Removing sebastian/diff (6.0.2)
  - Removing sebastian/environment (7.2.0)
  - Removing sebastian/exporter (6.3.0)
  - Removing sebastian/global-state (7.0.2)
  - Removing sebastian/lines-of-code (3.0.1)
  - Removing sebastian/object-enumerator (6.0.1)
  - Removing sebastian/object-reflector (4.0.1)
  - Removing sebastian/recursion-context (6.0.2)
  - Removing sebastian/type (5.1.2)
  - Removing sebastian/version (5.0.2)
  - Removing staabm/side-effects-detector (1.0.5)
  - Removing theseer/tokenizer (1.2.3)
Writing lock file
Installing dependencies from lock file (including require-dev)
Package operations: 0 installs, 0 updates, 26 removals
  - Removing theseer/tokenizer (1.2.3)
  - Removing staabm/side-effects-detector (1.0.5)
  - Removing sebastian/version (5.0.2)
  - Removing sebastian/type (5.1.2)
  - Removing sebastian/recursion-context (6.0.2)
  - Removing sebastian/object-reflector (4.0.1)
  - Removing sebastian/object-enumerator (6.0.1)
  - Removing sebastian/lines-of-code (3.0.1)
  - Removing sebastian/global-state (7.0.2)
  - Removing sebastian/exporter (6.3.0)
  - Removing sebastian/environment (7.2.0)
  - Removing sebastian/diff (6.0.2)
  - Removing sebastian/complexity (4.0.1)
  - Removing sebastian/comparator (6.3.1)
  - Removing sebastian/code-unit-reverse-lookup (4.0.1)
  - Removing sebastian/code-unit (3.0.3)
  - Removing sebastian/cli-parser (3.0.2)
  - Removing phpunit/phpunit (11.5.19)
  - Removing phpunit/php-timer (7.0.1)
  - Removing phpunit/php-text-template (4.0.1)
  - Removing phpunit/php-invoker (5.0.1)
  - Removing phpunit/php-file-iterator (5.1.0)
  - Removing phpunit/php-code-coverage (11.0.9)
  - Removing phar-io/version (3.2.1)
  - Removing phar-io/manifest (2.0.4)
  - Removing myclabs/deep-copy (1.13.1)
  0/16 [>---------------------------]   0%
 10/16 [=================>----------]  62%
 16/16 [============================] 100%
Generating optimized autoload files
> Illuminate\Foundation\ComposerScripts::postAutoloadDump
> @php artisan package:discover --ansi

   INFO  Discovering packages.  

  laravel/breeze ........................................................ DONE
  laravel/pail .......................................................... DONE
  laravel/sail .......................................................... DONE
  laravel/tinker ........................................................ DONE
  livewire/livewire ..................................................... DONE
  livewire/volt ......................................................... DONE
  nesbot/carbon ......................................................... DONE
  nunomaduro/collision .................................................. DONE
  nunomaduro/termwind ................................................... DONE

56 packages you are using are looking for funding.
Use the `composer fund` command to find out more!
> @php artisan vendor:publish --tag=laravel-assets --ansi --force

   INFO  No publishable resources for tag [laravel-assets].  

No security vulnerability advisories found
./composer.json has been updated
Running composer update pestphp/pest pestphp/pest-plugin-laravel
Loading composer repositories with package information
Updating dependencies
Lock file operations: 40 installs, 0 updates, 0 removals
  - Locking brianium/paratest (v7.8.3)
  - Locking doctrine/deprecations (1.1.5)
  - Locking fidry/cpu-core-counter (1.2.0)
  - Locking jean85/pretty-package-versions (2.1.1)
  - Locking myclabs/deep-copy (1.13.1)
  - Locking pestphp/pest (v3.8.2)
  - Locking pestphp/pest-plugin (v3.0.0)
  - Locking pestphp/pest-plugin-arch (v3.1.1)
  - Locking pestphp/pest-plugin-laravel (v3.2.0)
  - Locking pestphp/pest-plugin-mutate (v3.0.5)
  - Locking phar-io/manifest (2.0.4)
  - Locking phar-io/version (3.2.1)
  - Locking phpdocumentor/reflection-common (2.2.0)
  - Locking phpdocumentor/reflection-docblock (5.6.2)
  - Locking phpdocumentor/type-resolver (1.10.0)
  - Locking phpstan/phpdoc-parser (2.1.0)
  - Locking phpunit/php-code-coverage (11.0.9)
  - Locking phpunit/php-file-iterator (5.1.0)
  - Locking phpunit/php-invoker (5.0.1)
  - Locking phpunit/php-text-template (4.0.1)
  - Locking phpunit/php-timer (7.0.1)
  - Locking phpunit/phpunit (11.5.15)
  - Locking sebastian/cli-parser (3.0.2)
  - Locking sebastian/code-unit (3.0.3)
  - Locking sebastian/code-unit-reverse-lookup (4.0.1)
  - Locking sebastian/comparator (6.3.1)
  - Locking sebastian/complexity (4.0.1)
  - Locking sebastian/diff (6.0.2)
  - Locking sebastian/environment (7.2.0)
  - Locking sebastian/exporter (6.3.0)
  - Locking sebastian/global-state (7.0.2)
  - Locking sebastian/lines-of-code (3.0.1)
  - Locking sebastian/object-enumerator (6.0.1)
  - Locking sebastian/object-reflector (4.0.1)
  - Locking sebastian/recursion-context (6.0.2)
  - Locking sebastian/type (5.1.2)
  - Locking sebastian/version (5.0.2)
  - Locking staabm/side-effects-detector (1.0.5)
  - Locking ta-tikoma/phpunit-architecture-test (0.8.5)
  - Locking theseer/tokenizer (1.2.3)
Writing lock file
Installing dependencies from lock file (including require-dev)
Package operations: 40 installs, 0 updates, 0 removals
  - Downloading pestphp/pest-plugin (v3.0.0)
  - Downloading phpunit/phpunit (11.5.15)
  - Downloading jean85/pretty-package-versions (2.1.1)
  - Downloading fidry/cpu-core-counter (1.2.0)
  - Downloading brianium/paratest (v7.8.3)
  - Downloading phpstan/phpdoc-parser (2.1.0)
  - Downloading phpdocumentor/reflection-common (2.2.0)
  - Downloading doctrine/deprecations (1.1.5)
  - Downloading phpdocumentor/type-resolver (1.10.0)
  - Downloading phpdocumentor/reflection-docblock (5.6.2)
  - Downloading ta-tikoma/phpunit-architecture-test (0.8.5)
  - Downloading pestphp/pest-plugin-arch (v3.1.1)
  - Downloading pestphp/pest-plugin-mutate (v3.0.5)
  - Downloading pestphp/pest (v3.8.2)
  - Downloading pestphp/pest-plugin-laravel (v3.2.0)
  0/15 [>---------------------------]   0%
  3/15 [=====>----------------------]  20%
  5/15 [=========>------------------]  33%
 11/15 [====================>-------]  73%
 13/15 [========================>---]  86%
 15/15 [============================] 100%
  - Installing pestphp/pest-plugin (v3.0.0): Extracting archive
  - Installing sebastian/environment (7.2.0): Extracting archive
  - Installing staabm/side-effects-detector (1.0.5): Extracting archive
  - Installing sebastian/version (5.0.2): Extracting archive
  - Installing sebastian/type (5.1.2): Extracting archive
  - Installing sebastian/recursion-context (6.0.2): Extracting archive
  - Installing sebastian/object-reflector (4.0.1): Extracting archive
  - Installing sebastian/object-enumerator (6.0.1): Extracting archive
  - Installing sebastian/global-state (7.0.2): Extracting archive
  - Installing sebastian/exporter (6.3.0): Extracting archive
  - Installing sebastian/diff (6.0.2): Extracting archive
  - Installing sebastian/comparator (6.3.1): Extracting archive
  - Installing sebastian/code-unit (3.0.3): Extracting archive
  - Installing sebastian/cli-parser (3.0.2): Extracting archive
  - Installing phpunit/php-timer (7.0.1): Extracting archive
  - Installing phpunit/php-text-template (4.0.1): Extracting archive
  - Installing phpunit/php-invoker (5.0.1): Extracting archive
  - Installing phpunit/php-file-iterator (5.1.0): Extracting archive
  - Installing theseer/tokenizer (1.2.3): Extracting archive
  - Installing sebastian/lines-of-code (3.0.1): Extracting archive
  - Installing sebastian/complexity (4.0.1): Extracting archive
  - Installing sebastian/code-unit-reverse-lookup (4.0.1): Extracting archive
  - Installing phpunit/php-code-coverage (11.0.9): Extracting archive
  - Installing phar-io/version (3.2.1): Extracting archive
  - Installing phar-io/manifest (2.0.4): Extracting archive
  - Installing myclabs/deep-copy (1.13.1): Extracting archive
  - Installing phpunit/phpunit (11.5.15): Extracting archive
  - Installing jean85/pretty-package-versions (2.1.1): Extracting archive
  - Installing fidry/cpu-core-counter (1.2.0): Extracting archive
  - Installing brianium/paratest (v7.8.3): Extracting archive
  - Installing phpstan/phpdoc-parser (2.1.0): Extracting archive
  - Installing phpdocumentor/reflection-common (2.2.0): Extracting archive
  - Installing doctrine/deprecations (1.1.5): Extracting archive
  - Installing phpdocumentor/type-resolver (1.10.0): Extracting archive
  - Installing phpdocumentor/reflection-docblock (5.6.2): Extracting archive
  - Installing ta-tikoma/phpunit-architecture-test (0.8.5): Extracting archive
  - Installing pestphp/pest-plugin-arch (v3.1.1): Extracting archive
  - Installing pestphp/pest-plugin-mutate (v3.0.5): Extracting archive
  - Installing pestphp/pest (v3.8.2): Extracting archive
  - Installing pestphp/pest-plugin-laravel (v3.2.0): Extracting archive
  0/39 [>---------------------------]   0%
 10/39 [=======>--------------------]  25%
 20/39 [==============>-------------]  51%
 29/39 [====================>-------]  74%
 39/39 [============================] 100%
4 package suggestions were added by new dependencies, use `composer suggest` to see details.
Generating optimized autoload files
> Illuminate\Foundation\ComposerScripts::postAutoloadDump
> @php artisan package:discover --ansi

   INFO  Discovering packages.  

  laravel/breeze ........................................................ DONE
  laravel/pail .......................................................... DONE
  laravel/sail .......................................................... DONE
  laravel/tinker ........................................................ DONE
  livewire/livewire ..................................................... DONE
  livewire/volt ......................................................... DONE
  nesbot/carbon ......................................................... DONE
  nunomaduro/collision .................................................. DONE
  nunomaduro/termwind ................................................... DONE
  pestphp/pest-plugin-laravel ........................................... DONE

88 packages you are using are looking for funding.
Use the `composer fund` command to find out more!
> @php artisan vendor:publish --tag=laravel-assets --ansi --force

   INFO  No publishable resources for tag [laravel-assets].  

No security vulnerability advisories found
Using version ^3.8 for pestphp/pest
Using version ^3.2 for pestphp/pest-plugin-laravel

   INFO  Installing and building Node dependencies.  


added 198 packages, and audited 199 packages in 20s

49 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

> build
> vite build

vite v6.3.5 building for production...
✓ 53 modules transformed.
public/build/manifest.json             0.27 kB │ gzip:  0.14 kB
public/build/assets/app-DOgJ2e88.css  38.10 kB │ gzip:  6.88 kB
public/build/assets/app-T1DpEqax.js   35.28 kB │ gzip: 14.13 kB
✓ built in 2.73s
   INFO  Livewire scaffolding installed successfully.  

   INFO  Application ready in [laravel11-task]. Build something amazing.
