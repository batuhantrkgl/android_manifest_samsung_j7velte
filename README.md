# Skyhawk Recovery Project

### How to build ###

```bash
# Create dirs
$ mkdir skyhawk ; cd skyhawk

# Init repo
$ repo init --depth=1 -u git://github.com/SKYHAWK-Recovery-Project/platform_manifest_twrp_omni.git -b 9.0

# Clone my local repo
$ git clone https://github.com/samsungexynos7870/android_device_samsung_j7velte.git -b skyhawk device/samsung/j7velte

# Sync
$ repo sync --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j`nproc`

# Build
$ mv device/samsung/j7velte/build_skyhawk.sh .
$ . build_skyhawk.sh j7velte
```

## Credits
2019 @Astrako

## Contact
Telegram support group: https://t.me/joinchat/D1Jk_VbieGBXOWZt2y8O7A
