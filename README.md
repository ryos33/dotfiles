# dotfiles

```
cd 
git clone https://github.com/ryos33/dotfiles.git
ln -s ~/dotfiles/_bash_profile .bash_profile
ln -s ~/dotfiles/_vimrc .vimrc
ln -s ~/dotfiles/_gvimrc .gvimrc
wget https://raw.github.com/git/git/master/contrib/completion/git-completion.bash -O .git-completion.bash
wget https://raw.github.com/git/git/master/contrib/completion/git-prompt.sh -O .git-prompt.sh

mkdir .vimbackup

source .bash_profile
```
