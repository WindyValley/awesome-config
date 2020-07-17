# 此仓库由 "GNU与Linux技术分享" 腾讯 QQ 群群员创建，如果你也想加入 QQ 群那就快来吧!

**1 群: 823167016** </br>
**2 群: 466898428**

### 欢迎在这里分享你的配置文件!

*注意事项*
- 如果可以排序，请尽量排序，Emacs 用户开启 markdown-mode 后可以使用 "C-c C-c ^" 排序
- Emacs表格格式无法对齐请设置等高等宽字体，例如Iosevka，配置例子:
  ```emacs-lisp
  (if (fontp (font-spec
				   ;; :name "Fira Code Nerd Font" 
				   ;; :style "Retina"
				   :name "Iosevka"
				   :style "Regular"
				   ;; :name "Sarasa Mono SC"
				   ;; :style "Regular"
				   )) 
		   (set-face-attribute 'default nil 
							   :font (font-spec 
									  ;; :name "Fira Code Nerd Font"
									  ;; :style "Retina"
									  :name "Iosevka"
									  :style "Regular"
									  ;; :name "Sarasa Mono SC"
									  ;; :style "Regular"
									  :size 20)) 
		 (message "无法找到Sarasa Mono SC字体，你可以更换其他字体或安装它让这条消息消失.")
  ```

| GitHub                                        | QQ 群名片    | 博客                                           | dotfiles                                                     | vim                                                 | emacs                                                                                                                                | 介绍                                                                                                                                |
|-----------------------------------------------|--------------|------------------------------------------------|--------------------------------------------------------------|-----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| [Augists](https://github.com/Augists)         | 长大池子     | NULL                                           | NULL                                                         | [ZDCZ-vimrc](https://github.com/Augists/ZDCZ-vimrc) | NULL                                                                                                                                 | vimrc 配置，基于 **macOS 10.15.4**                                                                                                  |
| [ChunjieShan](https://github.com/ChunjieShan) | 单胖         | NULL                                           | [.config](https://github.com/ChunjieShan/.config)            | [PangVim](https://github.com/ChunjieShan/PangVim)   | NULL                                                                                                                                 | 我的 config 文件中包括我的 dwm，st，scripts, ranger 等日常工作配置，同时包含我根据 CW，ThinkVim 和自己的使用习惯配置的 NeoVim 配置  |
| [Dimerbone](https://github.com/Dimerbone)     | 思钱想厚     | [DiBlog](https://dimerbone.github.io)          | [dotfiles](https://github.com/dimerbone/Origin)              | [vim](https://github.com/dimerbone/Origin)          | NULL                                                                                                                                 | Origin Repo 中包含适用于 Arch 系的 i3、polybar、ranger、vim、rofi、dunst 等配置                                                     |
| [EvanMeek](https://github.com/EvanMeek)       | EvanMeek     | [我不会编程的博客](https://evanmeek.github.io) | [dotfiles](https://github.com/EvanMeek/dotfiles)             | NULL                                                | [doom-emacs](https://github.com/EvanMeek/dotfiles/tree/master/doom.d) [Evan-Emacs](https://github.com/EvanMeek/.emacs.d "EvanEmacs") | dotfiles 中包含 alacritty、fish shell、fcitx、i3wm、polybar、rofi 等配置                                                            |
| [Innei](https://github.com/Innei)             | Innei        | [静之林](https://shizuri.net)                  | [dotfiles](https://github.com/innei/dotfiles)                | [nvim](https://github.com/innei/nvim)               | NULL                                                                                                                                 | neovim 配置，dotfiles 中包含 zsh, fzf, git config, tmux                                                                             |
| [KiteAB](https://github.com/KiteAB)           | KiteAB       | [KiteAB's Blog](https://kiteab.github.io)      | [dotfiles](https://github.com/KiteAB/.config)                | [nvim](https://github.com/KiteAB/nvim)              | NULL                                                                                                                                 | 适用于 Arch Linux 的配置文件                                                                                                        |
| [UniqueDing](https://github.com/UniqueDing)   | 回忆心酸的痛 | [uniqueding](http://uniqueding.cn)             | [dotfiles](https://github.com/UniqueDing/linux-config-files) | NULL                                                | NULL                                                                                                                                 | dotfiles 中有 ranger、i3、fish、vim (dwm、st、dmenu)等配置                                                                          |
| [KyleJKC](https://github.com/KyleJKC)         | KyleJKC      | [啥也没有的博客](https://kylejkc.github.io)    | NULL                                                         | [Neovim](https://github.com/KyleJKC/nvim)           | NULL                                                                                                                                 | 一个及其现代好用的 Neovim 配置                                                                                                      |
| [vritser](https://github.com/vritser)         | vritser      | [半斤八两](https://vritser.github.io)          | [dotfiles](https://github.com/vritser/dotfiles)              | NULL                                                | [Emacs](https://github.com/vritser/.emacs.d)                                                                                         | macOS 平台, Hammerspoon 做窗口管理, 键盘布局 Dvorak 配合 Emacs [xah-fly-keys](http://ergoemacs.org/misc/xah-fly-keys_tutorial.html) |
| [logicskky](https://github.com/logicskky)     | logicskky    | NULL                                           | [dotfiles](https://github.com/logicskky/dotfiles)            | [LogicVim](https://github.com/logicskky/LogicVim)   | NULL                                                                                                                                 | dotfiles 中有 ranger、dwm、st、dmenu 等配置                                                                                         |
| [VainJoker](https://github.com/vainjoker)     | Vain Joker   | [Nothing](http://vainjoker.cn)                 | [dotfiles](https://github.com/vainjoker/myconfig)            | [Myivm](https://github.com/vainjoker/Myvim)         | [MyEmacs](https://github.com/vainjoker/MyEamcs)                                                                                      | 一些好玩的东西（dwm,st,emacs,vim,rime,好看的字体及其对应的自动化部署脚本                                                            |
