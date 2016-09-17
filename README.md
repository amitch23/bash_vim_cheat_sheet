# bash_vim_cheat_sheet

Common commands for bash and vim

## BASH Know-how 

### Help
| Key/Command | Description |
| ----------- | ------------|
| [command] -h	|Offers help|
| info [command]|	offers help|
| man [command]|	Show help manual|
| apropos [search-pattern]	|Searches for command with keywords in description|

### Line shortcuts
|Key/Command|	Description|
|-----------|	-----------|
|Ctrl + U	|Cut everything back to beginning of line|
|Ctrl + K	|Cut everything forward to front of line|
|Ctrl + W	|Cut one word backwards|
|Ctrl + Y	|Paste last command that was cut|
|Ctrl + A	|Go to beginning of line|
|Ctrl + E	|Go to end of line|

### Search and command history
|Key/Command	|Description|
|-----------|	-----------|
|find [dir] -name [search_pattern]|search for files, e.g. find /Users -name “file.txt”|
|grep [search_pattern] [file]|	Search for all lines that contain the pattern|
|history n	 |shows stuff typed with num to limit items|
|Ctrl + r	|interactive search through past commands|
|!!|	Execute the last command typed|

### Chaining Commands
|Key/Command|	Description|
|-----------|	-----------|
|"[command-a];[command-b]"	|Run commands asynchronously|
|"[command-a] &&|[command-b]"|	Run commands synchronously|
|[command-a] &| Run command in background|
|[command-a] | [command-b]|	"Run command then pass result to command B|


### MISC:
|Key/Command|	Description|
|-----------|	-----------|
|cd 	|defaults to go home|
|cd + -	|Previous directory|
|pbcopy < [file]	|Copy file contents to clipboard|
|pbpaste > [file]|	Paste clipboard contents|
|mkdir -p [dir]/[dir]	|Create nested directories|

## VIM  

 Vim has (at least) 3 modes: insert mode, command mode, and last-line mode. When you run `vi <file>` it opens in --command mode. This means that all the alphanumeric keys are bound to commands, not their actual values in insert mode.
 
 To enter the insert mode, type `i` (for "insert") and now the keys will behave as you'd expect. You can type normally until you want to make a correction, save the file, or perform another operation that's reserved for command mode or last-line mode. To get out of insert mode and back into command mode, hit the `Esc` key.
 
 `:` gets you to the last-line mode, where you can "save" or `w` (write), or quit, `q`. To save and quit, `ZZ` in command mode, or type `:wq`. To quit without saving, `:q!`
 
### Navigation in command mode:
 
|Key/Command|Description|
|-----------|-----------|
|G |move to the end of the file.|
|gg| move to the beginning of the file.|
|0 |moves the cursor to the beginning of the line.|
|$ |moves the cursor to the end of the line.|
|`.| move to the last edit.|

WTF:
-ifconfig?
-network stuff?
-how is command history saved and why is it saved when I open a new session?
-open 1password with keyboard shortcut
	
	
