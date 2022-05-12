FFmpeg README
=============

FFmpeg is a collection of libraries and tools to process multimedia content
such as audio, video, subtitles and related metadata.

## Libraries

* `libavcodec` provides implementation of a wider range of codecs.
* `libavformat` implements streaming protocols, container formats and basic I/O access.
* `libavutil` includes hashers, decompressors and miscellaneous utility functions.
* `libavfilter` provides a mean to alter decoded Audio and Video through chain of filters.
* `libavdevice` provides an abstraction to access capture and playback devices.
* `libswresample` implements audio mixing and resampling routines.
* `libswscale` implements color conversion and scaling routines.

## Tools

* [ffmpeg](https://ffmpeg.org/ffmpeg.html) is a command line toolbox to
  manipulate, convert and stream multimedia content.
* [ffplay](https://ffmpeg.org/ffplay.html) is a minimalistic multimedia player.
* [ffprobe](https://ffmpeg.org/ffprobe.html) is a simple analysis tool to inspect
  multimedia content.
* Additional small tools such as `aviocat`, `ismindex` and `qt-faststart`.
* [liblav](https://libav.org/) is a audio and video processing tool.
* [sox](http://sox.sourceforge.net/) SoX can play and record audio files on most platforms.
* [soxmirror](https://github.com/chirlu/sox) SoX can play and record audio files on most platforms same thing.
* [audacity](https://www.audacityteam.org/) multi-track editor.

## Documentation

The offline documentation is available in the **doc/** directory.

The online documentation is available in the main [website](https://ffmpeg.org)
and in the [wiki](https://trac.ffmpeg.org).

and a unofficial [discord](https://discord.gg/qa82ND9Nbr)

### Examples

Coding examples are available in the **doc/examples** directory.

## License

FFmpeg codebase is mainly LGPL-licensed with optional components licensed under
GPL. Please refer to the LICENSE file for detailed information.

## Contributing

Patches should be submitted to the ffmpeg-devel mailing list using
`git format-patch` or `git send-email`. Github pull requests should be
avoided because they are not part of our review process and will be ignored.

## Apps Been Used
* [obs](https://obsproject.com/) streaming and recording
* [sunvox](https://warmplace.ru/soft/sunvox/) that uses liblav and music software
* [fl studio](https://www.image-line.com/) that uses a plugin by fl studio for vizulizer
* [danser](https://github.com/Wieku/danser-go) that uses osu for map so it autoplays your maps from osu
* [osr2mp4](https://github.com/uyitroa/osr2mp4-app) using replays on osu same for dancer
* [osr2mp4-fourm](https://osu.ppy.sh/community/forums/topics/1104243?n=1) it's a real forum that created osr2mp4
* [replaymod](https://osu.ppy.sh/community/forums/topics/1104243?n=1) minecraft mod uses replays from minecraft
* [blender](https://www.blender.org/) 3d animating software
