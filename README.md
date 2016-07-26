My tmux configuration

### Install tmux

```bash
$ sudo apt-get install tmux
```

### Install dependency

```bash
$ sudo apt-get install xsel
```

### Configuration

```bash
$ cd
$ git clone https://github.com/jarsonfang/tmux.git
$ ln -sf tmux/tmux.conf .tmux.conf
$ ln -sf tmux/tmux-statusline.conf .tmux-statusline.conf
```

add the following line to `~/.bash_aliases` file and then `source ~/.bash_aliases`:
```bash
alias tmux='tmux -2'
```
