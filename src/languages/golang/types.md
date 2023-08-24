# [Types](https://go.dev/ref/spec#Types)

A quick summary on common types and now to initialise them with inference.

## Basic types

```go
age := 18       // int
amount := 10.99 // float
a := 'a'        // rune (char / ascii value)
t := true       // bool
name := "John"  // string
```

## Array

Arrays have a size known at compile time but cannot resize, used when you ahve a fixed amount of data you need to store.

Generally more efficient than slices.

```go
arr := [2]string{"a","b"}   // string array 
```

## Slice

Can be resized

```go
// Slices
arr := []string{"a","b"}    // string slice (dynamic size)
arr := []int{1,2}           // int slice
```

### Maps

```go
m := make(map[string]int)   // map of string keys to int values
m["John"] = 30              // assinging to a map

m := map[string]int{        // declare map with values
    "John" : 30
}
```
