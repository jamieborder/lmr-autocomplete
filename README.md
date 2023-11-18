# Tab completes for lmr
[lmr (née eilmer)](https://github.com/gdtk-uq/gdtk)

## For bash terminals:
(may need sudo)
```
cp lmr /etc/bash_completion.d/
. /etc/bash_completion.d/lmr
```

## For zsh terminals:
```
mkdir ~/.zsh-completions
cp _lmr ~/.zsh-completions/
echo 'fpath=( ~/.zsh-completions $fpath )
autoload -Uz compinit && compinit' >> ~/.zshrc
```
