# ArrowOS Android 10;

### How to build ###

```bash
# Create dirs
$ mkdir arrowOS-10 ; cd arrowOS-10

# Init repo
$ repo init -u https://github.com/ArrowOS/android_manifest.git -b arrow-10.0

# Clone a3y17lte repo
$ git clone https://github.com/batuhantrkgl/android_manifest_samsung_j7velte/ -b arrowOS-10-test device/samsung/j7velte

# Sync
$ repo sync --force-sync --no-clone-bundle -j$(nproc --all)

# Build
$  . build/envsetup.sh
$ . build_ofox.sh j7velte
```

## Credits
```
2019 @Astrako
2022 @Batuhantrkgl
```

## Contact
Telegram support group: https://t.me/joinchat/D1Jk_VbieGBXOWZt2y8O7A
