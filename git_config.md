[alias]
s = status
co = checkout
f = fetch --all --prune
h = log -20 --decorate --graph --pretty=format':%C(yellow)%h%Creset%C(auto)%d%Creset - %C(bold blue)%an%Creset (%C(green)%ar%Creset) - %s'
hall = log --decorate --graph --pretty=format':%C(yellow)%h%Creset%C(auto)%d%Creset - %C(bold blue)%an%Creset (%C(green)%ar%Creset) - %s'
hh = log -20 --decorate --all --graph --pretty=format':%C(yellow)%h%Creset%C(auto)%d%Creset - %C(bold blue)%an%Creset (%C(green)%ar%Creset) -
%s'
hhh = log --decorate --all --graph --pretty=format':%C(yellow)%h%Creset%C(auto)%d%Creset - %C(bold blue)%an%Creset (%C(green)%ar%Creset) -
%s'


meta repo

$ cd
$ git clone https://gerrit.googlesource.com/git-repo

.bashrc
```
# add git-repo to PATH
if [ -d "$HOME/git-repo" ] ; then
PATH="$HOME/git-repo:$PATH"
fi
```
repo version
more info in: https://source.android.com/setup/develop/repo#start
