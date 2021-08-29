# fcitx5-icons

Default fcitx5 icon for chinese pinyin and korean hangul is too ugly, found some nice alternatives and here is how to replace the old icons.

`cn_icon.png` is from [JeroGC/fcitx5-simple-theme](https://github.com/JeroGC/fcitx5-simple-theme)

`kr_icon.png` is from [South Korea icon by Icons8](https://icons8.com/)

### Chinese pinyin icon update

Download `cn_icon.png` icon and move to the following directory.

`/usr/share/icon/hicolor/48x48/apps/cn_icon.png`

Make symlink to point icon of pinyin input method to new image(you may need to delete or backup the old one).

`sudo ln -s /usr/share/icon/hicolor/48x48/apps/fcitx-pinyin.png /usr/share/icon/hicolor/48x48/apps/cn_icon.png`

### Korean hangul icon update

Download `kr_icon.png` icon and move to the following directory.

`/usr/share/icon/hicolor/64x64/apps/kr_icon.png`

Make symlink to point icon of korean hangul input method to new image(you may need to delete or backup the old one).

`sudo ln -s /usr/share/icon/hicolor/64x64/apps/fcitx-hangul.png /usr/share/icon/hicolor/64x64/apps/kr_icon.png`
