# Photo Gallery App

A photo gallery web application written in AngularDart and Aqueduct

## Pre-requisites

1. Install `webdev` tool: `pub global activate webdev`
2. Install Aqueduct cli >v4: `pub global activate aqueduct 4.0.0-b1`

## Running packages

### pg_client

```bash
$ cd pg_client # cd into client package
$ pub get # Update dependencies
$ webdev serve # launch local web server
```

### pg_server

```bash
$ cd pg_server # cd into server package
$ pub get # Update dependencies
$ aqueduct serve # launch local web server
```