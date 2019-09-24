# git-configuration
Carry my own git configuration where ever I go! Run the following commands to get the new environment up and running.

### aliases
```
git config --global alias.lg "log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen[%ai](%ar) %C(bold blue)<%an>%Creset' --abbrev-commit"
git config --global alias.ls "diff-tree --no-commit-id --name-only -r"
git config --global alias.rl "reflog --date=iso"
git config --global alias.aliases "! git config --get-regexp ^alias\. | sed -e s/^alias\.// -e s/\ /\ =\ /"
```

### resources
https://devhints.io/git-log
