# Control flow

The basics of logic in go, the main difference from other languages is that go does all loops via for.

## If

```go
a := 10
if a > 1 {
    ...
}

// or
if a := 10; a > 1 {
    ...
}

// will see things like this a lot
if err := doSomething() ; err != nil {
    ...
}
```

## Loops

Only one loop keyword in go `for`

```go
// Basic for
for i := 0; i<10; i++ {
    ...
}

// Forever
for {
    ...
    break // end the loop
}

// Same as a while loop
i := 20
for i < 10 {
    i--
}
```

##  Range loop

Special loop available in Go for looping over arrays, slices and maps, range returns two values, in slices and arrays the first value will be the index and the second the value. with maps the first will be the key.

```go
// Slices and Arrays
alphabet := []string{"a", "b"}
for index, value := range alphabet {
    fmt.Println(index, value)
}
// 0 a
// 1 b

// Maps
people := map[string]int{
    "Bob", 20
}
for key, value := range people {
    fmt.Println(key, value)
}
// bob 20
```
