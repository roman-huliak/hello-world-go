# hello-world-go
"hello world" in go


To run the program, put the code in app.go and use go run.

$ go run app.go
hello world

Sometimes we’ll want to build our programs into binaries. We can do this using go build.
$ go build app.go
$ ls
app app.go


We can then execute the built binary directly.
$ ./app
hello world
