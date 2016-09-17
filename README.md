## BASH Know-how 

### Help
| Key/Command | Description |
| ----------- | ------------|
| [command] -h	|Offers help|
| info [command]|	offers help|
| man [command]|	Show help manual|
| apropos [Search-pattern]	|Searches for command with keywords in description|

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
|find [dir] -name [Search_pattern]|Search for files, e.g. find /Users -name “file.txt”|
|grep [Search_pattern] [file]|	Search for all lines that contain the pattern|
|history n	 |Show stuff typed with num to limit items|
|Ctrl + r	| Search interactively through past commands|
|!!|	Execute the last command typed|

### Chaining Commands
|Key/Command|	Description|
|-----------|	-----------|
|[command-a] ; [command-b]	|Run commands asynchronously|
|[command-a] && [command-b]|Run commands synchronously|
|[command-a]  &| Run command in background|
|[command-a] \| [command-b]|	Run command then pass result to command B|


### MISC:
|Key/Command|	Description|
|-----------|	-----------|
|cd 	|Change Directory to home|
|cd + -	|Go to previous directory|
|pbcopy < [file]	|Copy file contents to clipboard|
|pbpaste > [file]|	Paste clipboard contents|
|mkdir -p [dir]/[dir]	|Create nested directories|

## VIM  

 Vim has (at least) 3 modes: insert mode, command mode, and last-line mode. When you run `vi <file>` it opens in --command mode. This means that all the alphanumeric keys are bound to commands, not their actual values in insert mode.
 
 To enter the insert mode, type `i` (for "insert") and now the keys will behave as you'd expect. You can type normally until you want to make a correction, save the file, or perform another operation that's reserved for command mode or last-line mode. To get out of insert mode and back into command mode, hit the `Esc` key.
 
 `:` gets you to the last-line mode, where you can "save" or `w` (write), or quit, `q`. To save and quit, `ZZ` in command mode, or type `:wq`. To quit without saving, `:q!`
 
### Navigation in command mode:
 
|Key/Command|	Description|
|-----------|	-----------|
|G | Move to the end of the file.|
|gg| Move to the beginning of the file.|
|0 |Moves the cursor to the beginning of the line.|
|$ |Moves the cursor to the end of the line.|
|`.| Move to the last edit.|

### Editing in command mode:

|Key/Command|	Description|
|-----------|	-----------|
|d | Start the delete operation.|
|dw |Delete a word to the right.|
|d0 |Delete to the beginning of a line.|
|d$ |Delete to the end of a line.|
|dgg |Delete to the beginning of the file.|
|dG | Delete to the end of the file.|
|u | Undo the last operation.|
|Ctrl-r | Redo the last undo.|
	
### Search and Replace:

|Key/Command|	Description|
|-----------|	-----------|
|/[text]| Search for text in the document, going forward.|
|n |Move the cursor to the next instance of the text from the last Search. This will wrap to the beginning of the document.|
|N |Move the cursor to the previous instance of the text from the last Search.|
|?[text]| Search for text in the document, going backwards.|
|:%s/text/replacement text/g |Search through the entire document for text and replace it with replacement text.|
|:%s/text/replacement text/gc |Search through the entire document and confirm before replacing text.|

### Search and Replace:
In command mode, hit `v` or `V` to highlight by word or line. Select text then...


|Key/Command|	Description|
|-----------|	-----------|
|y |Yank text into the copy buffer.|
|p |Paste text after the current line.|
|P |Paste text on the current line.|

### Miscellaneous 

#### 1Password (Works in browsers with the browser extension installed.)

|Key/Command|	Description|
|-----------|	-----------|
|Command‑Backslash (\\)|	Fill Login on current web page.|
|Option‑Command‑Backslash (\\)	| Show 1Password mini.|
|Control‑Option‑Command‑L|	Lock 1Password.|

