---
id: 1708961122-HGVW
aliases:
  - install-executable
tags:
  - Executable
  - Golang
---

# install-executable

Installing an executable is the process of creating an executable and storing it in
$GOPATH/bin. The go install command works just like go build, but go install takes
care of placing the output file in the right place for you.
```bash
go install hello
```
If $GOPATH/bin is part of your $PATH environment variable, the executable will be available from anywhere on your operating system. You can verify its location using which command

```bash
which hello
```


