# Style Guide

## Go

### Static Code Checking
For vim users, add the [vim-go](https://github.com/fatih/vim-go) plugin. After installing, run `:GoInstallBinaries`

For non-vim users, run `go fmt` in the folder of `.go` files. `go fmt` autofixes linting issues.

Instead of `go fmt`, you can use [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) to easily update your Go import lines, adding missing ones and removing unreferenced ones. It's a drop-in replacement for your editor's gofmt-on-save hook. It has the same command-line interface as gofmt and formats your code in the same way.

Other tools you can use to check your code statically are `go vet` and [golint](https://github.com/golang/lint).
* `go vet` reports "suspicious constructs, such as Printf calls whose arguments do not align with the format string. Vet uses heuristics that do not guarantee all reports are genuine problems, but it can find errors not caught by the compilers."
* Golint differs from govet. Govet is concerned with correctness, whereas golint is concerned with coding style. Golint is in use at Google, and it seeks to match the accepted style of the open source Go project.

### Code Coverage
Commands to run
1. `go test -coverprofile=coverage.out`
1. `go tool cover -html=coverage.out`

https://blog.golang.org/cover

## SQL
http://www.sqlstyle.guide/

Use the river indent if your SQL statement spans more than one line
