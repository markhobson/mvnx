# Maven Extras

Simple CLI scripts for working with Maven.

## mvn-init

Script to create a simple POM for a new project.

Installation:

```bash
curl -so ~/bin/mvn-init https://raw.githubusercontent.com/markhobson/mvnx/master/mvn-init && chmod +x ~/bin/mvn-init
```

Usage:

```bash
mvn-init
```

This will prompt you for some basic information and create a `pom.xml`.

## mvn-settings

Script to easily switch between different Maven `settings.xml` files. Add files of the form `~/.m2/settings.<name>.xml` and it will symlink between them.

Installation:

```bash
curl -so ~/bin/mvn-settings https://raw.githubusercontent.com/markhobson/mvnx/master/mvn-settings && chmod +x ~/bin/mvn-settings
```

Usage:

```bash
mvn-settings <name>
```

This will symlink `~/.m2/settings.xml` to `~/.m2/settings.<name>.xml`.
