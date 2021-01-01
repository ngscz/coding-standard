# NGS - Coding standard

## Installation

```
composer require ngscz/coding-standard --dev
```

## Usage

Create file `ruleset.xml` in root.

```
<?xml version="1.0"?>
<ruleset name="Boutiq">
    <arg name="basepath" value="."/>
    <rule ref="vendor/ngscz/coding-standard"/>

    <!-- Directories to be checked -->
    <file>app</file>
</ruleset>
```

PHPCS

```
#!/bin/sh

php vendor/bin/phpcs --standard=ruleset.xml
```

PHPCBF

```
#!/bin/sh

php vendor/bin/phpcbf --standard=ruleset.xml
```