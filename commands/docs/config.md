---
title: config
categories: |
  env
version: 0.84.0
env: |
  Edit nushell configuration files.
usage: |
  Edit nushell configuration files.
---

# <code>{{ $frontmatter.title }}</code> for env

<div class='command-title'>{{ $frontmatter.env }}</div>

## Signature

```> config ```


## Input/output types:

| input   | output |
| ------- | ------ |
| nothing | string |

## Notes
You must use one of the following subcommands. Using this command as-is will only produce this help message.

## Subcommands:

| name                                             | type    | usage                                                                                                                                 |
| ------------------------------------------------ | ------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| [`config env`](/commands/docs/config_env.md)     | Builtin | Edit nu environment configurations.                                                                                                   |
| [`config nu`](/commands/docs/config_nu.md)       | Builtin | Edit nu configurations.                                                                                                               |
| [`config reset`](/commands/docs/config_reset.md) | Builtin | Reset nushell environment configurations to default, and saves old config files in the config location as oldconfig.nu and oldenv.nu. |