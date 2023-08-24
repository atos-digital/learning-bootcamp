# Variables

There are two ways to delcare vairables in golang

```go
var name string             // Empty value
var name string = "John"    // Initial value
```

and the more common one which we `should` use

```go
name := "John"  // Type inference to set type from value
```

This uses [type inference](https://en.wikipedia.org/wiki/Type_inference) to automatically detect the type based on the value.
