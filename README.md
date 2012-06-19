If-Carlsberg-Did-Configs
========================

Git
---

lg = log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative --all

source ~/.bash_addons/git-completion.bash PS1='\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;36m\]\W\[\033[00m\]$(__git_ps1 "(%s)") \$ '
