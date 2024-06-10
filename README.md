# Install Arch
- luks
- btrfs subvolumes for @, @home, @pkg @log
- install yay
- nvidia-dkms
  - https://github.com/korvahannu/arch-nvidia-drivers-installation-guide?tab=readme-ov-file
- hack nerdfont       
- lutris
  - epic game store
    - probably winetricks install c++
  - ffxiv
  - battle.net
    - d4
    - wow
- steam
  - BG3
  - Last Epoch
  - Path of Exile (proton compat)
- goverlay/mangohud -> set to f12
- set mangohud=1 in zshrc
- melkey vscode bindings/settings
- timeshift
```
#Oh-my-zsh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

#ZSH plugins
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
git clone https://github.com/agkozak/zsh-z ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-z

#Starship Prompt
curl -sS https://starship.rs/install.sh | sh

# Nerd Fonts - Hack font (via git)
git clone --depth 1 https://github.com/ryanoasis/nerd-fonts
cd nerd-fonts
./install.sh Hack
```
