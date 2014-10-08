ssh-init
========

ssh-init - utility for quick transfer of preferred settings to newly created remote host.

Requirements
============

* Linux or Mac OS X
* `ssh-copy-id` utility presence

Installation
============

* copy `.ssh-init.example` to `~/.ssh-init`
* define your own `REPO` and `INSTALL_CMD` inside `.ssh-init` file
* put `ssh-init` binary to your `PATH`
* use `ssh-init user@remote-host` for quick transfer of your preferences to remote host
