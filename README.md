# jsend

[![Build Status](https://travis-ci.org/jsvensson/jsend.svg?branch=master)](https://travis-ci.org/jsvensson/jsend)
[![PkgGoDev](https://pkg.go.dev/badge/github.com/jsvensson/jsend)](https://pkg.go.dev/github.com/jsvensson/jsend)

Golang **JSend** library


## Installation
```
$ go get github.com/jsvensson/jsend
```

## Usage

```go
import "github.com/jsvensson/jsend"
```

See [API documentation](https://pkg.go.dev/github.com/jsvensson/jsend).

## Format

JSend is a very simple json format to wrap your JSON responses.

```json
{
  "status": "success|fail|error",
  "data": {
    "your data": "here..."
  },
  "message": "error message when status is error"
}
```

See [the JSend specification](https://github.com/omniti-labs/jsend) for details.


## License

MIT. See [LICENSE](./LICENSE).
