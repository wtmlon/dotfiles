#### Wtmlon's dotfiles

bash + tmux + vim

##### Installation

##### Linux

```bash
# Copy and Enter installation
wget https://github.com/junegunn/fzf/releases/download/v0.67.0/fzf-0.67.0-linux_amd64.tar.gz; tar zxvf fzf-0.67.0-linux_amd64.tar.gz; mv fzf /usr/bin/; apt install -y silversearcher-ag; curl https://raw.githubusercontent.com/wtmlon/dotfiles/master/bootstrap.sh | bash
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

```

##### Main Plugin
- NerdTree
- ag (silversearcher)
- fzf (filename search & file content search)

