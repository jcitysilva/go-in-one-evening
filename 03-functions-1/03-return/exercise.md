# Returning a Value

Functions can return values. You need to define the type that the function returns.
You do it after the parentheses.

You can return either explicit values (like `12`) or a variable with matching type.

```go
func NumberOfMonths() int {
	return 12
}

func DaysInAWeek() int {
	days := 7
	return days
}
```

A function can take any number of arguments, separated by commas (`,`).

```go
func Add(x int, y int) int {
	sum := x + y
	return sum
}

func main() {
	five := Add(2, 3)
}
```

If arguments next to each other are of the same type, you can use a shorter form.
You can also write equations following the `return` immediately, with no additional variables.

```go
// Exactly the same thing
func Add(x, y int) int {
	return x + y
}
```

## Exercise

Exercise path: ./03-functions-1/03-return/main.go

Add the missing `Sum` function.

It should take 5 `int` arguments and return another integer, a sum of all arguments.

{{hints}}

{{hint 1}}

Don't forget the return type (`int`) before the opening brace of the function.

{{endhint}}

{{hint 2}}

Argument names need to start with a letter, so you can't just use `1`, `2`, `3`, `4`, `5`.
Try `a`, `b`, `c`, `d`, `e`, or something similar.

{{endhint}}

{{endhints}}
