dotfiles
========

my dotfiles

## install

clone repo to your local system into dir ~/dotfiles/
```
cd ~
git clone https://github.com/polarity/dotfiles.git
```

rename existing .bashrc for backup
```
mv .bashrc .bashrc_old
```
symlink dotfiles/.bashrc into home directory

```
ln -s dotfiles/.bashrc .bashrc
```

restart terminal session, enjoy
