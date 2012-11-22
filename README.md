Go Factorization
================

This is the [factorization kata][1] in [go][2].

The intent is to get to know [go][2] better.

Getting Started
---------------

We assume a working [go environment][3]

### Retrieving

The go documentation explains [workspaces][4]. In one of your
workspaces execute the following command

    go get github.com/dvberkel/go-factorization

This will clone the go-factorization repository from GitHub.

### Building

Change to the `github.com/dvberkel/go-factorization` directory. In
order to build the source run

    go build

This will create `go-factorization`, an executable that you can
execute with `./go-factorization`.

### Testing

    go test

is the command that executes all the tests.

### Contributing

When contributing code make sure to format it with the following
command

    go fmt

[1]: http://en.wikipedia.org/wiki/Kata_%28programming%29 "Wikipedia on Programming Katas"
[2]: http://golang.org/ "Go Homepage"
[3]: http://golang.org/doc/install "Getting started with go"
[4]: http://golang.org/doc/code.html "How to write go code"