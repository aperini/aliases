# Handy aliases

## Location: $HOME/.gitconfig
## Visualize: git alias

[alias]
    alias = config --get-regexp alias
    f = fetch
    p = pull
    ck = checkout
    cm = commit
    st = status
    br = branch
    rh = reset --hard
    type = cat-file
    dump = cat-file
    log1 = log --oneline --decorate
    hist = log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short
    on = show --pretty="" --name-only

more : http://durdn.com/blog/2012/11/22/must-have-git-aliases-advanced-examples/

## CMDER

%CMDER_ROOT%\config\aliases<br />
%CMDER_ROOT%\config\user-aliases.cmd<br />

;= @echo off<br />
;= rem Call DOSKEY and use this file as the macrofile<br />
;= %SystemRoot%\system32\doskey /listsize=1000 /macrofile=%0%<br />
;= rem In batch mode, jump to the end of the file<br />
;= goto:eof<br />
;= Add aliases below here<br />
e.=explorer .<br />
gl=git log --oneline --all --graph --decorate  $*<br />
ls=ls --show-control-chars -F --color $* -la<br />
pwd=cd<br />
clear=cls<br />
history=cat "%CMDER_ROOT%\config\.history"<br />
unalias=alias /d $1<br />
vi=vim $*<br />
cmderr=cd /d "%CMDER_ROOT%"<br />
..=cd ..<br />
...=cd ../..<br />
....=cd ../../..<br />
.....=cd ../../../..<br />
......=cd ../../../../..<br />
.......=cd ../../../../../..<br />


## ~/.bashrc

alias ll='ls -alF'<br />
alias la='ls -A'<br />
alias l='ls -CF'<br />
alias ..='cd ..'<br />
alias ...='cd ../..'<br />
alias ....='cd ../../..'<br />
alias .....='cd ../../../..'<br />
alias ......='cd ../../../../..'<br />
alias .......='cd ../../../../../..'<br />
