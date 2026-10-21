# Function Arguments

Functions can take arguments. Arguments are variables that are passed to the function.

Similarly to variables, you have to specify the argument's name and type.
You do it between the parentheses after the function's name.

```go
func PrintNumber(number int) {
	fmt.Println("My favorite number is", number)
}

func main() {
	// Prints: My favorite number is 5
	// number is equal to 5 inside the function
	PrintNumber(5)
}
```

## Exercise

Exercise path: ./03-functions-1/02-arguments/main.go

Write the missing `Greet` function. Call it once again in the `main`, so that the output is:

```bash
Hello, Alice
Hello, Bob
```

{{hints}}

{{hint 1}}

Function names are *case-sensitive*: `greet` won't work, it needs to be `Greet`.

{{endhint}}

{{endhints}}
