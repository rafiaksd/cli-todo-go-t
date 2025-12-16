# Todo CLI (Go)

A simple command-line todo app written in Go.

## Usage

Run the program with one of the following flags:

### Add a todo
```bash
go run . -add "Buy milk"
````

### List all todos

```bash
go run . -list
```

### Edit a todo

```bash
go run . -edit 0:Buy bread
```

### Toggle a todo (done / not done)

```bash
go run . -toggle 0
```

### Delete a todo

```bash
go run . -del 0
```

### To run using cli-todo.exe

Eg:

```bash
./cli-todo.exe -list
```

## Notes

* Todo indexes start from `0`
* Only one command can be used at a time
