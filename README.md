#### Wtmlon's dotfiles

bash + tmux + vim
<img width="1940" height="936" alt="image" src="https://github.com/user-attachments/assets/06492a7b-40ad-453e-a8d5-4311164b2709" />


##### Installation

##### Linux

```bash
# One-shot Installation
wget https://github.com/junegunn/fzf/releases/download/v0.67.0/fzf-0.67.0-linux_amd64.tar.gz; tar zxvf fzf-0.67.0-linux_amd64.tar.gz; mv fzf /usr/bin/; apt install -y silversearcher-ag bat; curl https://raw.githubusercontent.com/wtmlon/dotfiles/master/bootstrap.sh | bash

# Tmux One-shot build up.
apt install -y aptitude; aptitude install libevent-dev libncurses-dev; apt install -y libevent-dev libncurses-dev; wget https://github.com/tmux/tmux/releases/download/3.6a/tmux-3.6a.tar.gz; tar zxvf tmux-3.6a.tar.gz; cd tmux-3.6a; ./configure && make; make install

```

##### Mac:

```bash
wget -O - https://raw.githubusercontent.com/wtmlon/dotfiles/master/bootstrap.sh | bash
```

##### Some solution
- Mismatch of color in and out of tmux can be fixed by set $TERM=xscreen-256color (Out of tmux)
- cannt display Chinese in tmux(Use tmux -u to start an tmux session)

##### Usefull Commands
```bash
# Open Nerd tree
, + t

# search files by name(selected)
, + c

# search files by content
, + f

# search this files by name(selected)
[ + c

# search this files by content
[ + f

# git status
, + g

# save vim session
, + s

# load vim session
, + r

```
- also can use `vimm` alias command to load vim session

##### Main Plugin
- NerdTree
- ag (silversearcher)
- fzf (filename search & file content search)

