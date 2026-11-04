# hello

just say hello

## Install

import code

```bash
go get github.com/QwQljh/hello@latest
```

install cmd

```bash
go install github.com/QwQljh/hello/cmd/hello@latest
```

## Example

Here's a simple example as follows:

```go
package main

import (
  "fmt"
  "github.com/QwQljh/hello"
)

func main() {
  result := hello.Hello("jack")
  fmt.Println(result)
}
```