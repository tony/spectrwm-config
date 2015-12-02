spectrwm configuration
=====================

Version: tested on spectrwm 2.7.2

For use with conky-cli (Conky compiled without X) Includes conky command line file.

Installation
------------
  * `git clone https://github.com/tony/spectrwm-config.git ~/.spectrwm-tony`
  * `ln -s ~/.spectrwm-tony/.spectrwm.conf ~/.spectrwm.conf && ln -s ~/.spectrwm-tony/.conkyrc ~/.conkyrc`

Font
----
[Terminus](http://terminus-font.sourceforge.net/) is a crisp font pleasant to the eyes.

  * FreeBSD: `cd /usr/ports/x11-fonts/terminus-font/ && make install clean` or `pkg install terminus-font`
  * ArchLinux: `pacman -S terminus-font`
  * Debian / Ubuntu: `apt-get install xfonts-terminus`
  * Gentoo: `emerge -av media-fonts/terminus-font`
  * Fedora / CentOS / Redhat: `yum install terminus-fonts`

More
----

* More dot-configs: https://github.com/tony/.dot-config
* Github: http://www.github.com/tony
* Website: http://www.git-pull.com

