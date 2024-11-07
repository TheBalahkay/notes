---
id: 1708961720-ZIYX
aliases:
  - new-project
tags:
  - Golang
  - Setup
  - new-project
---

# new-project

```bash
mkdir myDir
cd myDir
go mod init myDir
```

Then make your go file inside `myDir`

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```
To run execute the main file with `go run`

```bash
go run {pathToMyFile}
```
you can compile the project into an [executable](make%20program%20executable.md) or
[install](install%20an%20executable.md) it to run it from anywhere on your system

