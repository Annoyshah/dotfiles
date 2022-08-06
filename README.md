<div align="center">
  <h3>─────※ ·❆· ※─────</h3>
</div>

<div align="center">
  <h2>:sparkles: <samp>INFORMATION </samp> </h2>
  <a href="https://github.com/riyuzenn/dotfiles#construction-installation"><b><samp> installation </samp></b></a> |
  <a href="https://github.com/riyuzenn/dotfiles/tree/f0fda40e80981fe46e552cc5f03195759f787c31"><b><samp> previous rice </samp></b></a> |
  <a href="https://github.com/riyuzenn/dotfiles#keyboard-keybindings"><b><samp> keybindings </samp></b></a> |
  <a href="https://github.com/riyuzenn/dotfiles#scroll-credits--inspiration"><b><samp> credits </samp></b></a> |
</div>
  <br>

   <img src="dekstop.png" alt="Rice Showcase" align="right" width="400px">
   List of configurations I used to personalize my own system.  
   
   Feel free to use it & share with others.
   
   For the inspiration & acknoledgement, kindly check the [credit](https://github.com/riyuzenn/dotfiles#credits--inspiration)
   section. This project would be nothing without them. 
   
   Here are more information about my setup:

   - **OS:** [arch](https://archlinux.org)
   - **WM:** [bspwm](https://github.com/baskerville/bspwm)
   - **Terminal:** [alacritty](https://github.com/alacritty/alacritty)
   - **Shell:** [zsh](https://www.zsh.org/)
   - **Panel:** [polybar](https://github.com/polybar/polybar)
   - **Compositor:** [picom](https://github.com/ibhagwan/picom)
   - **Editor:** [neovim](https://github.com/neovim/neovim)
   - **Notification:** [dunst](https://github.com/dunst-project/dunst)
   - **Launcher:** [rofi](https://github.com/davatorium/rofi)
  - **Fonts**: {[Fira Code](https://github.com/tonsky/FiraCode),[JetBrains Mono](https://github.com/JetBrains/JetBrainsMono), [Iosevka Nerd](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Iosevka), [Material Design Icon](https://github.com/google/material-design-icons)}
  
<br></br>  

## :construction: Installation

### arch linux

Installing dependencies. 

```sh
pacman -Sy xorg xorg-xinit xorg-xsetroot \
  nitrogen polybar dunst rofi alacritty neovim \
  bspwm sxhkd zsh firefox neofetch maim picom cava
  
# i use bspwm-rounded-corners & picom-ibhagwan
# for rounded window and kawase blur.
# https://aur.archlinux.org/packages/bspwm-rounded-corners
# https://aur.archlinux.org/packages/picom-ibhagwan-git

# oh-my-zsh installation
# sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

```
After installing denpendencies, you can now run the install script to automatically
create and write configurations.

```sh
$ chmod +x ./install && ./install
```

## :keyboard: Keybindings
 key | function |
| :--- | :-------- |
| <kbd>super</kbd> + <kbd>space</kbd> | open app launcher (rofi) |
| <kbd>super</kbd> + <kbd>Enter</kbd> | open terminal (alacritty) |
| <kbd>printscr</kbd> | screenshot (maim) |
| <kbd>super</kbd> + <kbd>q</kbd> | close window |
| <kbd>super</kbd> + <kbd>tab</kbd> | focus next window |
| <kbd>super</kbd> + <kbd>f</kbd> | toggle fullscreen |
| <kbd>super</kbd> + <kbd>t</kbd> | toggle tiled |
| <kbd>super</kbd> + <kbd>d</kbd> | toggle floating |
| <kbd>super</kbd> + <kbd>left click</kbd> | move floating window |
| <kbd>super</kbd> + <kbd>right click</kbd> | resize floating window |
| <kbd>super</kbd> + <kbd>1</kbd>-<kbd>5</kbd> | view workspace | 
| <kbd>super</kbd> + <kbd>shift</kbd> + <kbd>1</kbd>-<kbd>5</kbd> | move window to workspace | 
| <kbd>super</kbd> + <kbd>shift</kbd> + <kbd>r</kbd> | restart bspwm |
| <kbd>super</kbd> + <kbd>shift</kbd> + <kbd>q</kbd> | quit bspwm |

## :scroll: Credits & inspiration

- [aishenreemo](https://github.com/aishenreemo) (inspiration)
- [mountain theme](https://github.com/mountain-theme) (palette) 

