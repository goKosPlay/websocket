# ElasticPerch WebSocket

[![GoDoc](https://godoc.org/github.com/elasticperch/websocket?status.svg)](https://godoc.org/github.com/elasticperch/websocket)

ElasticPerch WebSocket was originally a fork of Gorilla Websocket and is a [Go](http://golang.org/) implementation of the
[WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) protocol.

---
The Gorilla project was archived on Dec 9, 2022. elasticperch/websocket was forked from the master branch and existing PRs & issues linked to those PRs were copied to this project.
Thank you to the Gorilla project maintainers for years of support, vision and direction for the community. 

This intention of the maintainers is to build on the original legacy while forming Our own vision and future for this project.
ElasticPerch/websocket is currently used in several Non-Profit & Commercial applications. Contributions are welcome.

---

### Documentation

<<<<<<< HEAD
* [API Reference](https://pkg.go.dev/github.com/elasticperch/websocket?tab=doc)
* [Chat example](https://github.com/elasticperch/websocket/tree/master/examples/chat)
* [Command example](https://github.com/elasticperch/websocket/tree/master/examples/command)
* [Client and server example](https://github.com/elasticperch/websocket/tree/master/examples/echo)
* [File watch example](https://github.com/elasticperch/websocket/tree/master/examples/filewatch)
=======
* [API Reference](https://pkg.go.dev/github.com/gorilla/websocket?tab=doc)
* [Chat example](https://github.com/gorilla/websocket/tree/master/examples/chat)
* [Command example](https://github.com/gorilla/websocket/tree/master/examples/command)
* [Client and server example](https://github.com/gorilla/websocket/tree/master/examples/echo)
* [File watch example](https://github.com/gorilla/websocket/tree/master/examples/filewatch)
* [Write buffer pool example](https://github.com/gorilla/websocket/tree/master/examples/bufferpool)
>>>>>>> enhancement/8-examples-to-save-memory-using-write-buffer-pool-and-freeing-nethttp-default-buffers

### Status

The ElasticPerch WebSocket package provides a complete and tested implementation of
the [WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) protocol. The
package API is stable.

### Installation

    go get github.com/elasticperch/websocket

### Protocol Compliance

The ElasticPerch WebSocket package passes the server tests in the [Autobahn Test Suite](https://github.com/crossbario/autobahn-testsuite) using the application in the [examples/autobahn subdirectory](https://github.com/elasticperch/websocket/tree/master/examples/autobahn).


### Special Thanks & History

[Gorilla Websocket](http://github.com/gorilla/websocket)
Gary Burd <gary@beagledreams.com>
Google LLC (https://opensource.google.com/)
Joachim Bauch <mail@joachim-bauch.de>
