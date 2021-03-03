# chromium-android-extension

Patches that add extension support to chromium on Android.

To apply, go into the `src` folder of chromium source tree and run `patch -p1 --ignore-whitespace -i ../patches/Extensions/{name_of_the_patch} --no-backup-if-mismatch` following the order in `series`.

The patches are last adapted to chromium version `88.0.4324.182`. Patches assume safe browsing is off and supervised user is disabled.