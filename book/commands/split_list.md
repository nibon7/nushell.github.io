---
title: split list
categories: |
  filters
version: 0.70.0
filters: |
  Split a list into multiple lists using a separator
usage: |
  Split a list into multiple lists using a separator
---

# <code>{{ $frontmatter.title }}</code> for filters

<div class='command-title'>{{ $frontmatter.filters }}</div>

## Signature

```> split list (separator)```

## Parameters

 -  `separator`: the value that denotes what separates the list

## Examples

Split a list of chars into two lists
```shell
> [a, b, c, d, e, f, g] | split list d
```

Split a list of lists into two lists of lists
```shell
> [[1,2], [2,3], [3,4]] | split list [2,3]
```
