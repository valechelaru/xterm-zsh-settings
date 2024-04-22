Combination of different settings collected from different sources to easily configure xterm and zsh on new systems.

Install xterm and/or uxterm, zsh and set is as the default shell. Also install powerlevel10k:

$ git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k #(clone it into ~/Sources or change the settings in the config files)

How to configure xterm:

$ xrdb -merge ~/.Xdefaults

References:

https://futurile.net/2016/06/14/xterm-setup-and-truetype-font-configuration/

https://github.com/Phantas0s/.dotfiles/tree/master/zsh
