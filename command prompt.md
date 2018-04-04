# Debian, Ubuntu, Mint
colored command prompt to include git status information if inside repo:
```bash
    export GIT_PS1_SHOWCOLORHINTS=1
#    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\]\w\[\033[00m\]$(__git_ps1)\$ '
    PROMPT_COMMAND='__git_ps1 "${debian_chroot:+($debian_chroot)}\[\033[01;35m\]\u@\h\[\033[0;37m\]:\[\033[0;36m\]\w\[\033[0;00m\]" " \[\033[0;36m\]>\[\033[0;00m\] "'
```

and the same stuff but without any colors
```bash
    PS1='${debian_chroot:+($debian_chroot)}\u@\h:\w$(__git_ps1)\$ '
```
