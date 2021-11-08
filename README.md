## VIM COMMANDS

Just a small list of some basic commands in [Vim](https://github.com/vim/vim). For a more in depth use vimtutor.

#### General Commands
- `:h [command]` -> Documentation of command. e.g. :h tabstop
- `:options` -> Brings up every vim option (like tabstop etc) and their documentation
- `:source %` -> Sources the current file
- `q:` -> Show command history
- `:pwd` -> Shows working directory in vim
- `:![command]` -> Switches to terminal to show the output of a command and  when you press 'Enter' switches back to vim. e.g. :!ls
- `:o [file]` -> Opens file. e.g. -o test.txt


#### Save and Exit

- `:wq` -> Save and close file
- `:w` -> Save
- `:q` -> Quit
- `:q!` -> Force quit (without changing the file)

#### Window Commands

- `ctrl+w+w` -> Changes tab when on split mode
- `ctrl+w+ -/+` -> Resize tabs. You may need to press shift and -/+  to work
- `:tabedit [file]` -> Open file in new tab. e.g. :tabedit test.txt
- `gt` -> Changes tab in vim

#### Editor Commands

- `u` -> Undo
- `/[input]` -> Searches in the current file. e.g. /plugin will search for word plugin
- `Esc` -> Exit insert mode
- `i` -> Enter insert mode
- `dd` -> Delete a line
- `:m .+1` -> Move current line one row down
- `:m .-2` -> Move current line one row up
- `:split` -> Splits editor horizontally
- `:vsplit` -> Splits editor vertically
- `:read ![command]` -> Inserts the output of the command into the current file in vim, one line below cursor. e.g. :read !cat .zshrc