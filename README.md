# .zsh
```bash
alias g=git
alias bb='code ~/.zshrc'
alias b='source ~/.zshrc'
```

# .ps

```
Set-Alias -Name g -Value git

function bb {
    code $profile
}

function b {
    . $profile
}
```


# git
```bash
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status
git config --global alias.pp pull --prune
```
