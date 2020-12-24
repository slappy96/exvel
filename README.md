# exvel
Complete dot files and config

Recommended for a fresh Arch Linux install.  Relevant details:

1. zsh -- zshell for all your heart desires
2. dwm -- outstanding suckless window manager
3. st_slappy -- st terminal customized
4. dmenu -- suckless program launcher
5. slstatus -- suckless status monitor

Things to consider after install:

1. If VCS (version control software) status at CLI desired:
		cd into .config/zsh/
		git clone https://github.com/olivierverdier/zsh-git-prompt.git
		close and re-open terminal
2. Browser -- download firefox (MOD+w) is dwm binding built in
3. Virtualization (MOD+v) is dwm binding for virt-manager
		pacman -Sy --needed \
		qemu \
		dhclient \
		openbsd-netcat \
		virt-viewer \
		libvirt \
		dnsmasq \
		dmidecode \
		ebtables \
		virt-install \
		virt-manager \
		bridge-utils
