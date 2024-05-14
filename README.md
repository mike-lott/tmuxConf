# tmuxConf
## Setup
From the cloned directlory, run `./setup.sh`. This will do the following:
* Create the directories `plugins/tpm/` in the current root directory
* Create a softlink, `~/.tmux.conf`, to the `tmux.conf` file in the current root directory
* Run the Tmux Plugin Manager so that any referenced plugins within the `tmux.conf` file are pulled down

Running `./setup.sh` will always check if the above files and directories are already present and will exit if it finds them.

## Remove
From the cloned directory, run `./remove.sh`. This will do the following:
* Delete the softlink, `~/.tmux.conf`
* Delete the cloned directory and all its contents
* The `remove.sh` will self-delete
