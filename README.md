gitconfig
=========

The gitconfig file I use:

```
[user]
    name = Andrew J. Pierce
    email = andrew.j.pierce@gmail.com
[core]
    editor = vim
[color]
    ui = auto
[alias]
    co = checkout
    ci = commit
    st = status
    br = branch
    pr = pull
    pod = push origin dev
    sui = submodule update --init
    hist = log --pretty=format:\"%h %ad | %s%d [%an]\" --graph --date=short
    type = cat-file -t
    dump = cat-file -p
[python "reindent"]
    path = /usr/share/doc/python2.7/examples/Tools/scripts/reindent.py
```