---
warning:     "This is a dynamically generated file. Do not edit manually."
layout:      "default"
title:       "var-name-mixedcase | Solhint"
date:        "Sun, 25 Aug 2019 22:09:19 GMT"
author:      "Peter Chung <touhonoob@gmail.com>"
---

# var-name-mixedcase
![Recommended Badge](https://img.shields.io/badge/-Recommended-brightgreen)
![Category Badge](https://img.shields.io/badge/-Style%20Guide%20Rules-informational)
![Default Severity Badge warn](https://img.shields.io/badge/Default%20Severity-warn-yellow)
> The {"extends": "solhint:recommended"} property in a configuration file enables this rule.


## Description
Variable name must be in mixedCase.

## Options
This rule accepts a string option of rule severity. Must be one of "error", "warn", "off". Default to warn.

### Example Config
```json
{
  "rules": {
    "var-name-mixedcase": "warn"
  }
}
```


## Examples
This rule does not have examples.

## Version
This rule was introduced in [Solhint 2.0.0-alpha.0](https://github.com/protofire/solhint/tree/v2.0.0-alpha.0)

## Resources
- [Rule source](https://github.com/protofire/solhint/tree/master/lib/rules/naming/var-name-mixedcase.js)
- [Document source](https://github.com/protofire/solhint/tree/master/docs/rules/naming/var-name-mixedcase.md)
- [Test cases](https://github.com/protofire/solhint/tree/master/test/rules/naming/var-name-mixedcase.js)
