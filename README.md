# test-language

---

A simple recursive descent (LL1) interpreter for a weird language. You can mess around with it [here](https://vrcxz.github.io/test-language/). Supports parsing of basic mathematical expressions (PMDAS), relation and logical operators. 

Example code [here](https://github.com/vrcxz/test-language/blob/main/guessing_game.weird).

---

## Language Constructs

`$var_name = value` = declares a variable

`fry value` = print

`prompt value` = print to prompt's output buffer

`pick var` = prompts for input

`👋👋 code 👋👋👋` = defines a scope

`oc(condition) 👋👋 code  👋👋👋` = if statement

`si(count)  👋👋 code 👋👋👋` = loop

`stahp` = breaks loop

`br` = prints newline

`clear` = clears prompt's output buffer
