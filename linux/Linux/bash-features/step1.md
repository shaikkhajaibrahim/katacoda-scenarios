# Understanding BASH Features
* When you login to the Server using any CLI based terminal you can see the view as shown in the terminal
* Execute the following commands to understand different shells available
`cat /etc/shells`{{execute}}

### Command Line History
* Command line history will be saved when you execute any command in the terminal
`history`{{execute}}

* Now to execute any command from history
```!<number>```
`!1`{{execute}}

### Command Line Editing
* Explore the following commands in the table to understand the command line edition


| Shortcut Key | Description |
| ------------ | ----------- |
| Ctrl+c | Sends the signal SIGINT to the current task which aborts or closes it |
| Ctrl+d | Closes the current shell prompt|
| Ctrl+e | Moves the cursor the end of the bash|
| Ctrl+f | Moves the cursor forward one character |
| Ctrl+g | Abort the research and restore the original file |
| Ctrl+k | It is used to delete the command from the curser to line home position|
| Ctrl+l | Clear the screen |
|