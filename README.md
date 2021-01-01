# NGS - Coding standard

## Installation

```
composer require ngscz/coding-standard --dev
```

## Usage

PHPCS

```
#!/bin/sh

php vendor/bin/phpcs --standard=vendor/ngscz/coding-standard/ruleset.xml
```

PHPCBF

```
#!/bin/sh

php vendor/bin/phpcbf --standard=vendor/ngscz/coding-standard/ruleset.xml
```