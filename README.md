# Monkey Interpreter in Go 🐵

This repository contains my code as I work through the book [**Writing An Interpreter In Go**](https://interpreterbook.com/) by Thorsten Ball.

The book walks step-by-step through building an interpreter for a simple programming language called **Monkey**, using the Go programming language.

---

## Features

- Lexer: tokenizes source code
- Parser: builds an abstract syntax tree (AST)
- Evaluator: interprets Monkey code
- REPL: interactive prompt for running Monkey programs

---

## Run the Interpreter

Make sure you have Go installed (1.18+ recommended).

```bash
go run main.go
```

Try it out:

```
>> let add = fn(a, b) { a + b; };
>> add(2, 3);
5
```

---

## Notes

This is a personal learning project based on the book.  
All credit to Thorsten Ball for the original design and ideas.

---

## License

For educational use only. See the book for full details.
