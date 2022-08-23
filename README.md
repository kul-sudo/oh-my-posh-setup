# oh-my-posh-setup
My personal Oh My Posh setup

# Windows 10/11
## Install
`scoop install https://github.com/JanDeDobbeleer/oh-my-posh/releases/latest/download/oh-my-posh.json`

## Fonts
https://ohmyposh.dev/docs/installation/fonts

## Making Powershell always run with the Oh My Posh profile
`notepad $PROFILE`\
The notepad opens up

`oh-my-posh init pwsh  --config "path\to\theme.json" | Invoke-Expression` has to be inserted into the file opened in the notepad

That's all.
