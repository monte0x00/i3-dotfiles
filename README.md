# monte0x00 i3-dotfiles ♥

### The **i3wm** & **alacritty** dotfiles! 

This is my very simple personal dotfiles, **pcmanfm** my application launcher and files manager, my shutdown and reboot are the commands in terminal and **firefox** is my notifications deamon.

## Dependencies
<img src="https://github.com/monte0x00/i3-dotfiles/blob/main/screenshot1.png" align="right" width="480px">

| desc.  | name |
| ------------- | ------------- |
|**wallpaper:** | [feh](https://wiki.archlinux.org/title/Feh)|
|**monitors config (optional):** | [xrandr](https://wiki.archlinux.org/title/Xrandr) |
|**terminal:** | [alacritty](https://github.com/alacritty/alacritty)|
|**file manager & application launcher:** | [pcmanfm](https://github.com/lxde/pcmanfm)|
|**screenshoter:** | [maim](https://github.com/naelstrof/maim) & [xclip](https://github.com/astrand/xclip)|

## Installation
1. Clone this repository.
    ```sh
    git clone https://github.com/monte0x00/i3-dotfiles.git
    ```

2. Install dependencies. (if you use another package manager like `apt` or `dnf`, use it)
- Arch
    ```sh
    sudo pacman -S feh xrandr alacritty pcmanfm maim xclip
    ```
- Debian
    ```sh
    sudo apt install feh xrandr alacritty pcmanfm maim xclip
    ```
- Fedora
    ```sh
    sudo dnf install feh xrandr alacritty pcmanfm maim xclip
    ```
3. Copy configs files.
    ```sh
    cd i3-dotfiles
    ```
    ```sh 
    cp -r i3 "$HOME/.config"
    ```
    ```sh
    cp -r alacritty "$HOME/.config"
    ```

3. Create feh directory & copy wallpaper.
    ```sh
    mkdir -p /usr/share/backgrounds
    ```
    ```sh
    cp -r wp.png /usr/share/backgrounds
    ```


5. Install the GTK theme, font and icon theme
- Download [Papirus Icon Theme (Red)](https://www.gnome-look.org/p/1166289/) and copy
    ```sh
    cp -r /usr/share/icons
    ``` 
- Download [Adwaita Color Variants (Red Dark)](https://www.gnome-look.org/p/1368915/) and copy
    ```sh
    cp -r /usr/share/themes
    ```
- Download [Iosevka Nerd Font](https://www.nerdfonts.com/font-downloads) and copy
    ```sh
    cp -r /usr/share/fonts
    ``` 

## Preview

![](https://github.com/monte0x00/i3-dotfiles/blob/main/screenshot1.png)
![](https://github.com/monte0x00/i3-dotfiles/blob/main/screenshot2.png)
![](https://github.com/monte0x00/i3-dotfiles/blob/main/wp.png)

## Keybinds
<img src="https://i.sstatic.net/gXQhI.jpg" align="right" width="300px">

Remember `win` refers to the `super / mod key`

|        keybind                             |                 function                 |
| ------------------------------------------ | ---------------------------------------- |
| win + t                                    | launch terminal (alacritty)              |
| win + e                                    | launch file manager (pcmanfm)            |
| win + shift + e                            | launch sudo pcmanfm                      |
| print                                      | screenshot (area selection)              |
| win + q                                    | close window                             |
| win + f                                    | fullscreen window                        |
| win + space                                | floating window                          |
| win + ←                                    | focus left window                        |
| win + ↓                                    | focus down window                        |
| win + ↑                                    | focus up window                          |
| win + →                                    | focus right window                       |
| win + shift + ←                            | move left window                         |
| win + shift + ↓                            | move down window                         |
| win + shift + ↑                            | move up window                           |
| win + shift + →                            | move right window                        |
| win + 1, 2, 3, 4, 5, 6, 7, 8, 9, 0         | workspaces switch                        |
| win + shift + 1, 2, 3, 4, 5, 6, 7, 8, 9, 0 | workspaces move focus window             |
| win + shift + r                            | restart i3                               |


## Style
<img src="https://github.com/monte0x00/i3-dotfiles/blob/main/style.png" align="right" width="180px">

| desc.  | name |
| ------------- | ------------- |
|**icons:** | [Papirus Icon Theme (Red)](https://www.gnome-look.org/p/1166289/)|
|**theme:** | [Adwaita Color Variants (Red Dark)](https://www.gnome-look.org/p/1368915/) |
|**font:** | [Iosevka Nerd Font](https://www.nerdfonts.com/font-downloads)|

## Contributions
you can to create issue or pull request.

distributed under the **[GPLv3+](https://www.gnu.org/licenses/gpl-3.0.html) license**.
<img src="https://www.gnu.org/graphics/gplv3-with-text-136x68.png" align="center" width="100px"> 
