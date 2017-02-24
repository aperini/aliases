# aliases

## CMDER

%CMDER_ROOT%\config\aliases<br />
%CMDER_ROOT%\config\user-aliases.cmd

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
