## VIM COMMANDS

Just a small list of some basic commands in [Vim](https://github.com/vim/vim). For a more in depth look use vimtutor.

#### General Commands
- :h [command] -> Documentation of command. e.g. :h tabstop
- :options -> Brings up every vim option (like tabstop etc) and their documentation
- :source % -> sources the current file
- q: -> show command history
- :pwd -> Shows working directory in vim
- :![command] -> Switches to terminal to show the output of a command and  when you press 'Enter' switches back to vim. e.g. :!ls


#### Save and Exit

- :wq -> save and close file
- :w -> save
- :q -> quit
- :q! -> force quit (without changing the file)

#### Window Commands

- ctrl+w+w -> changes tabs in vim
- ctrl+w+ -/+ -> resize tabs. You may need to press shift and -/+  to work

#### Editor Commands

- u -> undo
- /[input] -> searches in the current file. e.g. /plugin will search for word plugin
- Esc -> exit insert mode
- i -> enter insert mode
- dd -> delete a line
- :m .+1 -> move current line one row down
- :m .-2 -> move current line one row up
- :split -> Splits editor
- :read ![command] -> Inserts the output of the command into the current file in vim, one line below cursor. e.g. :read !cat .zshrc