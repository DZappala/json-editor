# Ratatui JSON Editor
This is a jaon editor made by following this (tutorial)[https://ratatui.rs/tutorials/json-editor] as expand my rust knowledge.

This is a simple tui that lets you create a json file by entering keys and values. It does not have any functionality beyond this.

# Build
*after cloning this repository*
```sh
cd ratatui-json
cargo run
```
# Usage
**\<q\>**: to quit
**\<e\>**: enter insert mode
**\<ESC\>**: enter normal mode

*While in edit mode*
**\<TAB\>**: toggle between key and value entry
**\<ENTER\>**: if the "key" box is selected, will move cursor to the "value" box. If "value" box is selected will write the new key-value pair to output. 

*After quitting*
Compiled JSON will appear inline in your terminal.
