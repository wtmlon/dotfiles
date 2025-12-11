#### Wtmlon's dotfiles

bash + tmux + vim
<img width="1940" height="936" alt="image" src="https://github.com/user-attachments/assets/06492a7b-40ad-453e-a8d5-4311164b2709" />


##### Installation

##### Linux

```bash
# Copy and Enter installation
wget https://github.com/junegunn/fzf/releases/download/v0.67.0/fzf-0.67.0-linux_amd64.tar.gz; tar zxvf fzf-0.67.0-linux_amd64.tar.gz; mv fzf /usr/bin/; apt install -y silversearcher-ag; echo "alias vimm='vim -c \"source ~/vim-session.vim\"'" > ~/.bashrc; . ~/.bashrc; curl https://raw.githubusercontent.com/wtmlon/dotfiles/master/bootstrap.sh | bash
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

# search files by name
, + c

# search files by content
, + f

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

