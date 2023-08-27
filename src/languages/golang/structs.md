# Structs

The core building block in golang, used to model data, create "instances" of resources, organise variables and scope functions on them.

```go
type Person struct{
    Name string
    Age int
}

var people []Person // Empty 

morePeople := []Person{} // Empty

morePeople := []Person{
    {Name: "Bob", Age: 20},
    {Name: "Bill", Age: 40},
} // With values
```

## Methods

Methods are functions that are scoped to a struct

```go
type Person struct {
    Name string
    Age int 
}

func (p Person) Over18() bool {
    return p.Age >= 18
}

person1 := Person{Name: "Bob", Age: 20}
person1.Over18() // true
```
