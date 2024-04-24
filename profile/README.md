# Callisto
Callisto is a concatenative compiled programming language inspired by Forth and YSL-C3

It supports these compile targets:
- x86 real mode
- x86_64 Linux

with more coming soon

## Examples
### Hello world
```
include "cores/select.cal"
include "std/io.cal"

"Hello, world!" printlstr
```
