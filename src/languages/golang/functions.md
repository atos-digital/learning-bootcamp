# Functions

Functions in golang can return multiple values

```go
// Baisc function
func add(a int, b int) int {
    return a + b
}

// Same param types can be simplified
func add(a ,b int) int {
    return a + b
}

// Most functions return an error in go, multiple returns have brackets
func parse(s string) (int, error) {
    if s == "" {
        return 0, errors.New("no input")
    }
    ... // omited logic
    return i, nil
}
```
