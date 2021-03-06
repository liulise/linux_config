# i3wm + Manjaro 配置

## 用到的软件
- [i3-gaps](https://github.com/Airblader/i3)
- [polybar - 顶部工具栏](https://github.com/polybar/polybar)
- [dunst - 通知](https://github.com/dunst-project/dunst)
- [tmux - 终端复用器](https://github.com/tmux/tmux)
- [tpm - tmux插件管理](https://github.com/tmux-plugins/tpm)
- [neovim - vim](https://github.com/neovim/neovim)
    - [vim-plug - Vim插件管理](https://github.com/junegunn/vim-plug)
- [rofi - 启动器](https://github.com/davatorium/rofi)
- zsh
- [antigen - zsh插件管理](https://github.com/zsh-users/antigen)
- [alacritty - 终端](https://github.com/alacritty/alacritty)
- [bat - 替代cat](https://github.com/sharkdp/bat)
- [colorls - 替代ls](https://github.com/athityakumar/colorls)
- [picom - 美化](https://github.com/yshui/picom)
- [neofetch - 打印系统信息](https://github.com/dylanaraps/neofetch)

## 安装
```shell
sudo pacman -S i3-gaps polybar dunst neovim rofi alacritty bat picom neofetch tmux zsh

yay -S ruby-colorls antigen-git
```

## 更改Shell到Zsh
```shell
chsh -s /bin/zsh
```

## i3wm
![](./images/i3wm.png)

## 终端
![](./images/terminal.png)

## Vim
![](./images/neovim.png)

## Neofetch
![](./images/neofetch.png)

## Colorls
![](./images/colorls.png)
