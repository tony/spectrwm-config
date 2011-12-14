# Tony Narlock's scrotwm configuration

* Github: http://www.github.com/tony
* Website: http://www.git-pull.com

Version: scrotwm 0.9.23

For use with conky-cli (Conky compiled without X) Includes conky command line file.

Installation
------------
  * `git clone https://github.com/tony/scrotwm-config.git ~/.scrotwm-tony`
  * `ln -s ~/.scrotwm-tony/.scrotwm.conf ~/.scrotwm.conf && ln -s ~/.scrotwm-tony/.conkyrc ~/.conkyrc`

Font
----
[Terminus](http://terminus-font.sourceforge.net/) is a crisp font pleasant to the eyes.

  * FreeBSD: `cd /usr/ports/x11-fonts/terminus-font/ && make install clean` or `pkg_add -r terminus-font`
  * ArchLinux: `pacman -S terminus-font`
  * Debian / Ubuntu: `apt-get install xfonts-terminus`
  * Gentoo: `emerge -av media-fonts/terminus-font`
  * Fedora / CentOS / Redhat: `yum install terminus-fonts`
