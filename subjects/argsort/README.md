## argsort

### Instructions

Write a program that checks if an argument is sorted or not,the comparesion should be by index of ascii and  all printable characters will be used.

- Your Program should return `T` followed by a newline (`'\n'`) if the argument is sorted.
- Your Program should return `F` followed by a newline (`'\n'`) if the argument is not sorted.
- If the number of arguments is not 2 do nothing.

### Usage

And it's output should be:

```console
$ go run . | cat -e
$ go run . a | cat -e
T$
$ go run . " 5ABc" | cat -e
T$
$ go run . "zA1" | cat -e
F$
$ go run . "01Talent" "student" | cat -e
$ go run . "Hello World" | cat -e
F$
$ go run .  "a b c" | cat -e
F$
$ go run .  "   abc" | cat -e
T$
$ go run .  "    s" | cat -e
T$
$ go run .  "s    " | cat -e
F$
```