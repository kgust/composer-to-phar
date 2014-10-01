composer-to-phar
================

Convert Composer's vendor folder into a PHAR file.

## Installation

You can install box using one of the following methods:

Using Homebrew
```sh
brew install box
```

Via Composer
```sh
composer global require 'kherge/box=~2.4' --prefer-source
```

With cURL:
```sh
curl -LSs http://box-project.org/installer.php | php
```

## Building

To get help.
```sh
box help
```

To build the phar.
```sh
box build
```

To get information about the `box.json` file.
```sh
box help build | less
```
