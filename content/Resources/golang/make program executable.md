---
id: 1708961076-UFWE
aliases:
  - make-executable
tags: []
---

## make golang program executable

to build your program into a binary to run anywhere on your system 
***Note***: no output indicates a successful operation
```bash
go build Hello
```
To specify a different name or location for the executable, use the -o flag
```bash
go build -o build/hello hello
```
To run the file from anywhere you need to [install](install%20an%20executable.md) it


