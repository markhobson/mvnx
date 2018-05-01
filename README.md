# Maven Extras

Simple CLI commands for working with Maven.

## Installation

Install locally by running:

```bash
curl -so ~/bin/mvnx --create-dirs https://raw.githubusercontent.com/markhobson/mvnx/master/mvnx && chmod +x ~/bin/mvnx
```

Commands:

```
Usage: mvnx COMMAND

Commands:
  init      Create a simple POM for a new project
  settings  Switch between different Maven settings
```

## init

Command to create a simple POM for a new project:

```bash
Usage: mvnx init
```

This will prompt you for some basic information and create a `pom.xml`.

## settings

Command to easily switch between different Maven `settings.xml` files. Add files
of the form `~/.m2/settings.<name>.xml` and it will symlink between them.

```bash
Usage: mvnx settings <name>
```

This will symlink `~/.m2/settings.xml` to `~/.m2/settings.<name>.xml`.

Omit the name to display the currently configured `settings.xml`.
