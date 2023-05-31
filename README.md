# Golang Docker Git
Sometimes we need to download and get private golang modules which are in company git. for this we should run this command
`git config --global url."https://user:token@companygit.com/".insteadof "https://companygit.com/"`
and after that we can get modules with 
`go get privateModule`.

This image is build from `golang:1.20.1-alpine3.16` and there is `git` installed in it.
