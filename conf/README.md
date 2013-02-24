goconfig
========

This is a clone of https://code.google.com/p/goconf/

### Install

```bash
go get github.com/tillberg/goconfig
```

### Usage

```go
import conf "github.com/tillberg/goconfig"

func main() {
    config, err := conf.ReadConfigFile("something.ini")
}
```

See https://code.google.com/p/goconf/ for more details.
