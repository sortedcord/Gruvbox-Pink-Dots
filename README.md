# Gruvbox-Pink-Dots
All of the dot files and configurations for the Pink Gruvbox i3 theme.

![Screenshot](dev.png)

## What All I have themed

- i3 [WM]
- Edge Custom Theme [browser]
- Discord [Chat]
- Juno Theme [GTK3]
- Custom Terminal Colors [zsh/Kitty]
- Wal: VSCode theme [code editor]

## Installation

Clone this repository
``` 
git clone https://github.com/sortedcord/Gruvbox-Pink-Dots.git 
```

Install pywal -> https://github.com/dylanaraps/pywal

Copy the configurations
```
cp -r .config/* ~/.config/
```
### VS Code Theme

To use the vscode theme as shown in the screenshot, first set your wallpaper to `wall.jpg`
```
# install feh
yay -S feh
sudo apt install feh -y

feh --bg-set /path/to/wall.jpg
```

And then run `pywal -i /path/to/wall.jpg`

Install this VSCode plugin-

![Screenshot](extension.png)

Reopen VSCode and then it should automatically pick up on the generated theme.

### Install Chrome theme

Check out this repository to download the chrome theme

https://github.com/sortedcord/chrome-gruvbox

And you are done I suppose.


## Fonts used

| Font Name           | Usage         | Download                                                   
|---------------------|---------------|------------------------------------------------------------|
| Hack                | Terminal Font | https://github.com/source-foundry/Hack/releases/tag/v3.003 |
| Google Sans Display | Polybar Text  | https://fonts.google.com/specimen/Open+Sans                | 
| FontAwesome         | Polybar Icons | https://fontawesome.com/download                           |

