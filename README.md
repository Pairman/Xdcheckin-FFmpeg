# Xdcheckin-FFmpeg
Minimal FFmpeg with h.264 for Xdcheckin.

## Build Status
[![Build for macosx_12_7_x86_64](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-macosx_12_7_x86_64.yml/badge.svg)](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-macosx_12_7_x86_64.yml) <br>
[![Build for macosx_14_7_arm64](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-macosx_14_7_arm64.yml/badge.svg)](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-macosx_14_7_arm64.yml) <br>
[![Build for manylinux2010_i686](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-manylinux2010_i686.yml/badge.svg)](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-manylinux2010_i686.yml) <br>
[![Build for manylinux2010_x86_64](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-manylinux2010_x86_64.yml/badge.svg)](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-manylinux2010_x86_64.yml) <br>
[![Build for manylinux2014_aarch64](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-manylinux2014_aarch64.yml/badge.svg)](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-manylinux2014_aarch64.yml) <br>
[![Build for musllinux_1_1_i686](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-musllinux_1_1_i686.yml/badge.svg)](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-musllinux_1_1_i686.yml) <br>
[![Build for musllinux_1_1_x86_64](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-musllinux_1_1_x86_64.yml/badge.svg)](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-musllinux_1_1_x86_64.yml) <br>
[![Build for musllinux_1_2_aarch64](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-musllinux_1_2_aarch64.yml/badge.svg)](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-musllinux_1_2_aarch64.yml) <br>
[![Build for win32](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-win32.yml/badge.svg)](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-win32.yml) <br>
[![Build for win_amd64](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-win_amd64.yml/badge.svg)](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-win_amd64.yml) <br>
[![Build for win_arm64](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-win_arm64.yml/badge.svg)](https://github.com/Pairman/Xdcheckin-FFmpeg/actions/workflows/build-win_arm64.yml)

## Usage
Install:
```sh
pip install xdcheckin-ffmpeg
```

Import, get FFmpeg executable path and its version:
```python
import xdcheckin_ffmpeg
print(xdcheckin_ffmpeg.bin.ffmpeg()) # or xdcheckin_ffmpeg.ffmpeg()
print(xdcheckin_ffmpeg.bin.ffmpeg_version()) # or xdcheckin_ffmpeg.ffmpeg_version()
```

## Credits
[zimbatm/ffmpeg-static](https://github.com/zimbatm/ffmpeg-static) <br>
[fdk-acc-free](https://cgit.freedesktop.org/~wtay/fdk-aac/log/?h=fedora) <br>
[imageio/imageio-ffmpeg](https://github.com/imageio/imageio-ffmpeg)
