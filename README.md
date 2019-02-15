
# Assister

Python CLI Tool to simplify computing and enhance productivity

## Coming Soon
- Todo
- Calculator
- Script Manager

## Prerequisites
- Git
- Python3
- virtualenv

## Install

### Linux and macOS

- `git clone https://github.com/connormullett/assister.git`
- `cd assister`
- `virtualenv -p {/path/to/python3} venv`
- `source venv/bin/activate`
- `sh install.sh`

### Windows
Perform the following commands in PowerShell
- `git clone https://github.com/connormullett/assister.git`
- `cd assister`
- `python3 -m venv venv`
- `./venv/Scripts/activate.ps1`
- `./windows-install.sh`

### Dependancies are currently in the process of being removed and will
### no longer need a virtualenv

Running the install steps will allow you to call `assister` from your terminal
You will also have a new `todo.csv` file in the project base directory. This will hold all of the todos

## Commands
### Example
`assister -t create` 

`-t` - manages todos
    - `view` - view todos
    - `del {todo_id}` - delete todo by id
    - `create` - create a todo using a series of prompts
    - `mc {todo_id}` - mark todo complete
    - `mi {todo_id}` - mark todo incomplete

### Upcoming commands
 - incomplete
 - update elements

