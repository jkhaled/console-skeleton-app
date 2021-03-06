# Console skeleton application
Start point to build console application in PHP

## Foldering
```
├── bin
│   └── console.php
├── composer.json
├── composer.lock
├── config
│   └── routes.php
├── src
│   └── Command
│       ├── Conf.php
│       ├── Database.php
│       └── Download.php
└── vendor
    └── ...
```

## Getting Started
```bash
$ composer create-project gianarb/console-skeleton app 1.0.0
$ cd app
$ bin/console
```
This is the entrypoint of this application, the output is
```bash
✔ ~/git/console-skeleton-app
09:44 $ bin/console
 Skeleton App, version 0.0.1

Available commands:

 autocomplete  Command autocompletion setup
 hello         Good morning!! This is a beautiful day
 help          Get help for individual commands
 version       Display the version of the script
```

## Hello command
```bash
✔ ~/git/console-skeleton-app 
09:44 $ bin/console hello --name=John
Skeleton App, version 0.0.1

Hi John, you have call me. Now this is an awesome day!
```
