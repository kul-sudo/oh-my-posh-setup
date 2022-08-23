
![Screenshot 2022-08-24 025410](https://user-images.githubusercontent.com/95244851/186285969-f7694012-f834-4957-b35b-3d2dccaf5491.png)

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
