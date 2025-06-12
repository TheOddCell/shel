# `shel`
Very minimal shel, that is very customizable

## Installation
Download `shel`, then run it as `root` with the `--install` flag.
### Uninstallation
Run `shel --uninstall` as `root`

## Syntax
`cd` is `cd`.
`alias` lists aliases, use it in the form `alias something="somethingelse"`
`exit` exits the shell
use `#` for comments
`set` lists vars, `set VAR=VALUE` to set the variable to the value. Reccommended to use `add vars["VAR"]="VALUE"`.
`add` runs the following python commands as the shell. Can be used to set configs or rewrite the code.

## Customization
In the file `.shelconf`, write python code, that can be used to:
- Edit the prompt and other variables
- Rewrite the code to add stuff or remove stuff
- Run normal python on launch if you want
