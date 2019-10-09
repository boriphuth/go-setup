# go-setup
'
$ curl -O https://dl.google.com/go/go1.13.1.darwin-amd64.tar.gz
$ tar -xzf go1.13.1.darwin-amd64.tar.gz
$ mv go goroot
$ code . ~/.bash_profile
export GOROOT=~/goroot
export PATH=$PATH:$GOROOT/bin
'
