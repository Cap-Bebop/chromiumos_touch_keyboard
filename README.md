# Touch Keyboard

#### This is a fork of ChromiumOS [touch keyboard](https://chromium.googlesource.com/chromiumos/platform2/+/19effa94d56d31397a55292771c8ea196f419f1e/touch_keyboard/).

To get some details about the project, check the [README.upstream.md](README.upstream.md) file.

## Build and install

```
apt install build-essential cmake
mkdir build
cd build
cmake ../
make
sudo make install
```

Or just run the `dpkg-buildpackage -b --no-sign` command to build .deb package.

All Buttons are predefined and represent what's printed on the Keyboard except for 2 additions that are commonly used on small Laptop-Keyboards:  
`Fn+left = Home`  
`Fn+right = End`

## Configuration
To create a custom keyboard layout, edit the file layout.csv and place it as /etc/touch_keyboard/layout.csv.

**More info on customisation can be found in the [Wiki](https://github.com/jekhor/chromiumos_touch_keyboard/wiki).**
