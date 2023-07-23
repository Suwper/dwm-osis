
# what is this?

These are the configuration files for my dwm install

## Note
There are 2 versions available either with gaps or without, the one with gaps is not updated.


## Installation:


```bash
  git clone https://github.com/Suwper/dwm-osis
  cd dwm-osis
```
### After that cd into dmenu, dwmblocks(in whatever order you like).
```bash
    cd dmenu-5.2
    sudo make install
```
```bash
    cd dwmblocks
    sudo make install 
```
### Choose the version that suits you(with gaps or without).
#### for dwm with gaps.
```bash
    cd dwm-gaps
    sudo make install
```
#### for dwm without gaps(normal).
```bash
    cd dwm-norm
    sudo make install
```
### And create the .desktop file if needed.
```bash
    sudo touch /usr/share/xseesion/dwm.desktop
```
### Open the dwm.desktop file using you favorite text editor and write or copy and paste this into.
#### note: it will require to sudo privilages to write to this file.
```
    [Desktop Entry]
    Encoding=UTF-8
    Name=Dwm
    Comment=Dynamic window manager
    Exec=/usr/local/bin/dwm
    Icon=dwm
    Type=XSession
```

## Now start dwm and customize it to your liking.
