# go-intro
Foray into Google's Go(lang)

## Description 
This package serves as a playground to get started with the Go language. Check out this cool (article)[https://talks.golang.org/2012/splash.article] (sent to me by a friend) for the motivations behind Go

## Syntax of the Go language
### Variables in Go
There are 2 ways of doing this. Explicitly declaring the type of the variable or implicitly declaring a variable by assigning it a value and letting the compiler infer the type
```go
var someVariable int
someVariable = 8
```

```go
someVariable := 8
```

### Printing in Go
```go
import "fmt"

fmt.Println("This", "prints", "each", "word", "and adds a space automatically")
fmt.Print("All words are scrunched up with this print method.", "This word will come immediately after the full stop"
```

### Running Go programmes 
```go
go run main.go
```

```go 
go build main.go
```

### Functions in Go
```go
func someFunction(someVariable int) int {
  fmt.Println("Going to return some integer")
  return someVariable
}
```

### Pointers in Go
```go
someVariable := 100
var somePointer *int
somePointer = &someVariable
fmt.Println("Printing out the variable pointed to by the pointer", *SomePointer)
```

### If, else if, else conditionals 
```go 
func modifyVariable(var SomePointer *int) {
  *SomePointer += 1
}

*someVariablePtr := 8
modifyVariable(someVariablePtr)
fmt.Println("The new variable is:", someVariablePtr*)
```
