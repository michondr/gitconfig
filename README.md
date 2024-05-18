# gitconfig

forked from [porn/gitconfig](https://github.com/porn/gitconfig) few aliases that speed me up

# branches
```shell
git br
git co master
git up
git unfuck
git mkbranch ABC-123-some-feature
```

# rebase
```shell
git rb
git rbc
git rba
```

# commits
```shell
git ci
git cp
```
and some more
# Installation

* Download or clone the repository to some directory (e.g. `~/github/michondr/gitconfig/`).
```
cd
mkdir -p github/michondr
cd github/michondr
git clone https://github.com/michondr/gitconfig.git
```

* Include the gitconfig file in your `~/.gitconfig`:
```
[include]
	path = ~/github/michondr/gitconfig/gitconfig
...
```
This way your personal changes won't overwrite the file when you use:
```
git config --global user.name "James Bond"
git config --global user.email "jb@example.com"
```

## Global Ignore
Feel free to use my collection of file patterns I don't want to track:
* Symlink the global gitignore file to your home directory
```
ln -s ~/github/michondr/gitignore.global ~/.gitignore
```
