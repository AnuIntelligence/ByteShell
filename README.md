# ByteShell
# Custom CLI (Command Line Interface)

This is a custom command-line interface (CLI) implemented in C. It allows users to execute both built-in commands and non-built-in commands.

## Features

- Supports built-in commands: `cd`, `history`, `help`, `exit`.
- Executes non-built-in commands using `execvp`.
- Command history: Keeps track of previously entered commands.
- Simple and easy to use.

## Usage

1. Compile the source code:

```bash
gcc custom_cli.c -o custom_cli   
```
## Run the executable:  
```bash
./custom_cli
```
# Incomplete:Completing Soon
will be trying to add more features like `ls` `ctrl-c`
