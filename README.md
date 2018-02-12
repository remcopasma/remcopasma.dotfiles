# remcopasma.dotfiles

## How to Install the .profile file:

Download the file .profile and put the file into the root directory.
Than open youre terminal and type: source ~/.profile.

That is all.


## What is in this file and what are they doing:


######## Showing the weather in Amsterdam ########
alias weer="curl wttr.in/Amsterdam?0q"


######## Welcome text ########
echo "Hi Remco, nice to see you again!"

######### # Showing the files in your folder #########
alias ll="ls -lhA"


######### # open a folder #########
alias goto_fb="cd ~/mnt/c/Users/remco/Desktop/hvabackend"

######## Disk usage check ########
alias opslag="df -Tha --total"

The alias that i have made are things that are functional for me to use a few commands on a simple way.
