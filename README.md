@mate/mail
==========

An email client mate

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@mate/mail.svg)](https://npmjs.org/package/@mate/mail)
[![Downloads/week](https://img.shields.io/npm/dw/@mate/mail.svg)](https://npmjs.org/package/@mate/mail)
[![License](https://img.shields.io/npm/l/@mate/mail.svg)](https://github.com/emadridm/mail/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @mate/mail
$ mail COMMAND
running command...
$ mail (-v|--version|version)
@mate/mail/1.0.0 linux-x64 node-v16.1.0
$ mail --help [COMMAND]
USAGE
  $ mail COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`mail hello [FILE]`](#mail-hello-file)
* [`mail help [COMMAND]`](#mail-help-command)

## `mail hello [FILE]`

describe the command here

```
USAGE
  $ mail hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ mail hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/emadridm/mail/blob/v1.0.0/src/commands/hello.ts)_

## `mail help [COMMAND]`

display help for mail

```
USAGE
  $ mail help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_
<!-- commandsstop -->
