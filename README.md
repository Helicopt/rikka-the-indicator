# rikka-the-indicator

Linux terminal AI program

For Linux bash, add the following to .bashrc

```sh
PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u\[\033[00m\]@\[\033[01;32m\]\h\[\033[00m\] H \! C \# `rikka talk C-\#` \n\[\033[01;34m\]\W\[\033[00m\]\$ '
```
