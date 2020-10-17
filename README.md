# spectrwm configuration

Version: tested on spectrwm 2.7.2

For use with conky-cli (Conky compiled without X) Includes conky command line file.

# Installation

```sh
git clone https://github.com/tony/spectrwm-config.git ~/.spectrwm-tony
ln -s ~/.spectrwm-tony/.spectrwm.conf ~/.spectrwm.conf && ln -s ~/.spectrwm-tony/.conkyrc ~/.conkyrc
```

# Font

[Terminus] is a crisp font pleasant to the eyes.

- FreeBSD: [cd /usr/ports/x11-fonts/terminus-font/ && make install clean]{.title-ref} or [pkg
  install terminus-font]{.title-ref}
- ArchLinux: [pacman -S terminus-font]{.title-ref}
- Debian / Ubuntu: [apt-get install xfonts-terminus]{.title-ref}
- Gentoo: [emerge -av media-fonts/terminus-font]{.title-ref}
- Fedora / CentOS / Redhat: [yum install terminus-fonts]{.title-ref}

     [terminus]: http://terminus-font.sourceforge.net/

# More

- More dot-configs: <https://github.com/tony/.dot-config>
- Github: <http://www.github.com/tony>
- Website: <http://www.git-pull.com>
