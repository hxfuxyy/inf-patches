#Patches for InfinityX on Xiaomi Pad 5 (nabu)

Patches for compiling [ProjectInfinity-X](https://github.com/ProjectInfinity-X) (Android 16) on the Xiaomi Pad 5 (`nabu`).

## Contents

| File | Target |
|---|---|
| `frameworks_base.patch` | `frameworks/base` |
| `packages_apps_Settings.patch` | `packages/apps/Settings` |

## Usage
```bash
git clone https://github.com/hxfuxyy/inf-patches patches
cd frameworks/base && git apply ../../patches/frameworks_base.patch
cd packages/apps/Settings && git apply ../../../patches/packages_apps_Settings.patch
```

## Credits

- **[ArKT-7](https://github.com/ArKT-7)** 
- **[Sir_Torius](https://t.me/Sir_Torius)** 
