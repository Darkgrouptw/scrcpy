**This GitHub repo (<https://github.com/Genymobile/scrcpy>) is the only official
source for the project. Do not download releases from random websites, even if
their name contains `scrcpy`.**

# scrcpy on WSL
```sh
sudo apt update

# Do Not install adb, We will use window adb while adb.exe
sudo apt install ffmpeg libsdl2-2.0-0 wget \
                 gcc git pkg-config meson ninja-build libsdl2-dev \
                 libavcodec-dev libavdevice-dev libavformat-dev libavutil-dev \
                 libswresample-dev libusb-1.0-0 libusb-1.0-0-dev

cd scrcpy
./install_release.sh
```