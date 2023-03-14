# Intoduction

- Compiled
  - GO tool can run file directly, without VM
  - Executables are different for OS

- What can we do with go-lang
  - System apps to web Apps - Cloud

  
# Hello World in Go-Lang
``go mod init github.com/Mr-Sunglasses/hello``

```go min.go
package main

import "fmt"

func main() {
	fmt.Println("Hello World")
}

```

``go run <filename>``