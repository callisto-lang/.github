# Callisto
Callisto is a stack-safe concatenative compiled programming language

It supports these compile targets:
- x86 real mode
- x86_64 Linux, macOS
- [Uxn](https://100r.co/site/uxn.html)
- ARM64 Linux, macOS
- Lua (subset CallistoScript)

with more coming soon

IRC: callisto-lang on libera.chat

## Examples
### Hello world
```
include "cores/select.cal"
include "std/io.cal"

"Hello, world!" print_str
```
