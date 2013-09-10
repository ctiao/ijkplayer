ijkplayer
=========
Android MediaPlayer-like video player based on [ffplay](http://ffmpeg.org)

### My Build Enviroment
- Mac OS X 10.8.4
- ADT v22.0.4-741630
- NDK r9

### Dependent Tools (Mac OS X)
- MacPorts http://www.macports.org/install.php
 - sudo port -vd install git-core
 - sudo port -vd install ccache

### Build
	git clone https://github.com/bbcallen/ijkplayer.git ijkplayer
	cd ijkplayer
	git checkout -B stable n0.0.4
	sh init-submodules.sh
	sh compile-ffmpeg.sh
	sh compile-ijk.sh

### License
	Copyright (C) 2013 Zhang Rui <bbcallen@gmail.com> 
	Licensed under LGPLv2.1 or later

Other libraries projects are distributed on theirs own license:
- LGPL
  - FFmpeg http://git.videolan.org/?p=ffmpeg.git
  - libVLC http://git.videolan.org/?p=vlc.git
- Apache License v2
  - VitamioBundle https://github.com/yixia/VitamioBundle

