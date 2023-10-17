# Useful Linux commands 

[Learning Terminal Part 1](https://www.youtube.com/watch\?v\=XK81cfvrElg\&list\=PLc7fktTRMBozYfi4zlDeH0IdLdGImeOnO)

## Commands

- `cd` - Change Directory
- `more` - Used in conjunction with pipes "|" in commands that have longer results. Enables user to use arrow keys or space bar to scroll. Shift + Z + Z to exit.
- `echo` - Used to enter text in the terminal.
- `sudo` - Some commands need this as verification.
- `su` - Switch User
- `rm` - Remove file, `rm -Rf` to *recursively force* removing folders and its contents
- `mkdir` - Make Directory
- `ls` - List directory
- `mv` - Move/rename file/directory
- `pwd` - Print Working Directory
- `cp` - Copy files/directories
- `nano` - In terminal text editor
- `cat` - Show contents of file
- `chmod` - permissions modifications
- `chown` - change ownership
- `COMMAND --help` - quick access help guide
 
## Commands from [part 2](https://www.youtube.com/watch\?v\=kVlkgiwiY6w\&list\=PLc7fktTRMBozYfi4zlDeH0IdLdGImeOnO\&index\=2)

- `history` - Shows list of commands you've given. You could then use `!`+start of last command+`TAB`, to run a previous command. 
Or even `!`+Line Number. EXAMPLE = `!148` or `!nan`+`TAB` = nano .bashrc
- `grep` - Used in conjunction with any command that spits out a wall of text. 
Usage goes something like `ls -laR / | grep '*.mov'`. 
Probably a bad example, since I could've just done that with the ls command but hey.
- `df` - Disk Free `-h` for Human readable
- `ssh` - A way to securely access another computer. 
Usage `ssh <remote-user>@<destination-IP-or-DNS>`. `exit` to logout the remote computer.
- `ifconfig -a` - Find your internal IP address within your home network.
- `curl ifconfig.me` - This runs a script at https://ifconfig.me that executes a long list of commands that give you your external IP address (the internet facing one)
- `top` - Display the processes running
- `htop` - much more powerful version of `top`
