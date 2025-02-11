---
title: extern-wrapped
categories: |
  core
version: 0.84.0
core: |
  Define a signature for an external command with a custom code block.
usage: |
  Define a signature for an external command with a custom code block.
---

# <code>{{ $frontmatter.title }}</code> for core

<div class='command-title'>{{ $frontmatter.core }}</div>

## Signature

```> extern-wrapped (def_name) (params) (body)```

## Parameters

 -  `def_name`: definition name
 -  `params`: parameters
 -  `body`: wrapper code block


## Input/output types:

| input   | output  |
| ------- | ------- |
| nothing | nothing |

## Examples

Define a custom wrapper for an external command
```shell
> extern-wrapped my-echo [...rest] { echo $rest }; my-echo spam
╭───┬──────╮
│ 0 │ spam │
╰───┴──────╯

```

## Notes
This command is a parser keyword. For details, check:
  https://www.nushell.sh/book/thinking_in_nu.html