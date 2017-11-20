# Maven Extras

Simple CLI scripts for working with Maven.

## mvn-settings

Script to easily switch between different Maven `settings.xml` files. Add files of the form `~/.m2/settings.<name>.xml` and it will symlink between them.

Installation:

```bash
curl -so ~/bin/mvn-settings https://raw.githubusercontent.com/markhobson/mvnx/master/mvn-settings
```

Usage:

```bash
mvn-settings <name>
```

This will symlink `~/.m2/settings.xml` to `~/.m2/settings.<name>.xml`.
