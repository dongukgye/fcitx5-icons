# fcitx5-icons

Default fcitx5 icon for chinese pinyin and korean hangul is too ugly, found some nice alternatives and here is how to replace old icons.

### Chinese pinyin icon update

move `cn_icon.png` to `/usr/share/icon/hicolor/48x48/apps/cn_icon.png`.

make following symlink to point icon of pinyin input method to new image.

`sudo ln -s /usr/share/icon/hicolor/48x48/apps/fcitx-pinyin.png /usr/share/icon/hicolor/48x48/apps/cn_icon.png`

### Korean hangul icon update

move `kr_icon.png` to `/usr/share/icon/hicolor/64x64/apps/kr_icon.png`

make following symlink to point icon of korean hangul input method to new image.

`sudo ln -s /usr/share/icon/hicolor/64x64/apps/fcitx-hangul.png /usr/share/icon/hicolor/64x64/apps/kr_icon.png`
