# go-setup
```
$ curl -O https://dl.google.com/go/go1.13.1.darwin-amd64.tar.gz
$ tar -xzf go1.13.1.darwin-amd64.tar.gz
$ mv go goroot
$ code . ~/.bash_profile
# Go development
export GOROOT=$HOME/goroot
export PATH=$PATH:$GOROOT/bin
GO111MODULE=on


# export PS1='\h:\W \u\$ '
export PS1='$ '
[ -f ~/.kubectl_aliases ] && source ~/.kubectl_aliases

```
```
$ mkdir go && cd go && mkdir src && mkdir pkg && cd src && mkdir github.com && cd github.com && mkdir boriphuth && cd boriphuth

```
