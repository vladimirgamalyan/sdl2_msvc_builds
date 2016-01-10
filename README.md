# sdl2_msvc_builds #

[![Build status](https://ci.appveyor.com/api/projects/status/qp157wgdwefr9hq0?svg=true)](https://ci.appveyor.com/project/vladimirgamalian/sdl2-msvc-builds)

## Intro ##
Official SDL2 and satelite sources do not contain project files for Visual Studio 2015 yet. There are solution and project files for VS2015, an appveyor script, and ready binaries.
All solution and project files have been made by upgrade previous versions via Visual Studio 2015 CE, plus small fixes for include paths etc.

## Usage example ##
[neopedersia](https://github.com/vladimirgamalian/neopedersia/blob/master/appveyor.yml)

## Versions ##
 - SDL2-2.0.3
 - SDL2_image-2.0.1
 - SDL2_mixer-2.0.1
 - SDL2_net-2.0.1
 - SDL2_ttf-2.0.12

## Download binaries ##
  - [release (x86)](https://github.com/vladimirgamalian/sdl2_msvc_builds/releases/download/SDL2-Binaries/sdl2.zip)
  - [debug (x86)](https://github.com/vladimirgamalian/sdl2_msvc_builds/releases/download/SDL2-Binaries/sdl2d.zip)
  
Both (debug and release) versions contain:
  - SDL2.lib
  - SDL2.dll
  - SDL2.pdb
  - SDL2main.lib
  - COPYING.SDL2.txt
  - SDL2_mixer.lib
  - SDL2_mixer.dll
  - SDL2_mixer.pdb
  - COPYING.SDL2_mixer.txt
  - libFLAC-8.dll
  - libmodplug-1.dll
  - libogg-0.dll
  - libvorbis-0.dll
  - libvorbisfile-3.dll
  - smpeg2.dll
  - LICENSE.smpeg.txt
  - LICENSE.ogg-vorbis.txt
  - LICENSE.modplug.txt
  - LICENSE.FLAC.txt
  - SDL2_net.lib
  - SDL2_net.dll
  - SDL2_net.pdb
  - COPYING.SDL2_net.txt
  - SDL2_ttf.lib
  - SDL2_ttf.dll
  - SDL2_ttf.pdb
  - COPYING.SDL2_ttf.txt
  - libfreetype-6.dll
  - LICENSE.freetype.txt
  - SDL2_image.lib
  - SDL2_image.dll
  - SDL2_image.pdb
  - COPYING.SDL2_image.txt
  - libjpeg-9.dll
  - libpng16-16.dll
  - libtiff-5.dll
  - libwebp-4.dll
  - zlib1.dll
  - LICENSE.jpeg.txt
  - LICENSE.png.txt
  - LICENSE.tiff.txt
  - LICENSE.webp.txt
  - LICENSE.zlib.txt
  - all include files in include/SDL2 subdir

## License ##

sdl2_msvc_builds comes under zlib license, the same license as SDL2.
