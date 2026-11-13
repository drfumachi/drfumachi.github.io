Após a instalação do Debian com KDE Plasma segue alguns pacotes que devem ser
instalados:

1. sudo apt install git curl wget flatpak foot tmux neovim neovim-lualine lsd zsh

2. JetBrainsMono Nerd Font
2.1. Configurar as fontes em ~/.local/share/fonts
2.2. fc-cache -fv

3. Configurar o foot
3.1 definir o zsh como padrão chsh -s $(which zsh)
3.2 definir no foot.ini (configurações no site)

4. Oh-my-zsh -> sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

5. Configurar neovim

6. Configurar tmux
6.1. Configurar plugins do tmux (tpm)

7. configurar alias .zshrc para o ls com lsd

8. flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo

9. flatpak install flathub io.github.kolunmi.Bazaar
9.1. Firefox (flatpak)
9.2. sudo apt autoremove firefox-esr

10. sudo apt install -t trixie-backports linux-image-amd64 linux-headers-amd64
10.1. sudo apt update
10.2. ADICIONAL:
10.2.1. para instalação em pendrive: sudo apt update && sudo apt install firmware-linux firmware-misc-nonfree xserver-xorg-video-all
10.2.2. sudo update-initramfs -u -k all (regenerar a imagem de boot -> initramfs
para pegar todas as placas de vídeo no kernel)


11. Pihole
11.1. sudo contrab -e
11.1.1. 0 */6 * * * /usr/local/bin/pihole -g > /var/log/pihole-gravity-auto.log 2>&1




12. sudo apt install bibata-cursor-theme


