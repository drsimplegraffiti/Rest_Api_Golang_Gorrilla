##### Starting a go project

> mkdir -p $GOPATH/src/github.com/drsimplegraffiti/go_restApi_mux

##### Health check

```go
package main

import (
	"fmt"
)

func main() {
	fmt.Println("running...")
}

```

##### Build a go project

> go mod init "github.com/drsimplegraffiti/go_restApi_mux"

> go build

The `go build` command create the `.exe` file

- To run go project using the `.exe` command

Run: exe file ./go_restApi_mux

##### Import dependencies

```go

package main

import (
	"encoding/json"
	"log"
	"net/http"
	"math/rand"
	"strconv"
)

func main() {
}

```

---

#### import mux

> go get -u github.com/gorilla/mux

#### Starting server

go build && ./go_restApi_mux
