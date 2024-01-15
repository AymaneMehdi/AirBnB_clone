# AirBnB Clone Project

## Project Description
This project aims to create an AirBnB clone, starting with a command interpreter. The command interpreter allows managing various objects, such as creating, retrieving, updating, and deleting.

## Command Interpreter Description
To start the command interpreter, run `./console.py`. Once in the interactive mode, you can use commands like `help`, `quit`, and more. Non-interactive mode is also supported, as shown in the examples below:

```bash
$ echo "help" | ./console.py
$ cat test_help | ./console.py
```

## Examples
### Create a new User:
```bash
(hbnb) create User
```

### Retrieve an object:
```bash
(hbnb) show User 1234-5678
```

### Update attributes of an object:
```bash
(hbnb) update User 1234-5678 first_name "John"
```

### Destroy an object:
```bash
(hbnb) destroy User 1234-5678
```

## AUTHORS
Aymane Mehdi
Edmund VanDyck