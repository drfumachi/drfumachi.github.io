Após a instalação do Debian com KDE Plasma segue alguns pacotes que devem ser
instalados:

1. sudo apt install git curl tmux neovim neovim-lualine flatpak foot lsd zsh
wget
1.1 definir o zsh como padrão chsh -s $(which zsh)

1.2 definir no foot.ini

2. flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo

3. flatpak install flathub io.github.kolunmi.Bazaar
3.1. Firefox (flatpak)
3.2. sudo apt autoremove firefox-esr

4. sudo apt install -t trixie-backports linux-image-amd64 linux-headers-amd64
4.1. sudo apt update

5. JetBrainsMono Nerd Font
5.1. Configurar as fontes em ~/.local/share/fonts
5.2. fc-cache -fv

6. Oh-my-zsh -> sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

7. configurar alias .zshrc para o ls com lsd

8. 





