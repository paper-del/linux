env command shows all enviroment variables 
printenv HOME 
	displays the valoe of the HOME enviroment variable 

this is most common enviroment variables 
- `USER` - The current logged-in user.
- `HOME` - The home directory of the current user.
- `EDITOR` - The default file editor to be used. This is the editor that will be used when you type `edit` in your terminal.
- `SHELL` - The path of the current user’s shell, such as bash or zsh.
- `LOGNAME` - The name of the current user.
- `PATH` - A list of directories to be searched when executing commands. When you run a command the system will search those directories in this order and use the first found executable.
- `LANG` - The current locales settings.
- `TERM` - The current terminal emulation.
- `MAIL` - Location of where the current user’s mail is stored.
- `XDG_SESSION_TYPE` - The type of session (e.g., `tty`, `x11`, `wayland`).

set  and set | less
dispalys list of all variables

echo $bash_version 
	too print variables

var = "text"
	creates variable in terminal on one sesion
echo $var
	prints text
export var
	creates enviroment variable
export MY_NEW_VAR="My New Var"

export MY_NEW_VAR="My New Var"
	sets variable for a single command
	