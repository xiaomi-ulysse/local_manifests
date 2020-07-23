# Xiaomi Redmi Note 5A
This is the local manifest for syncing Redmi Note 5A Lite/Prime Device Trees automatically.

## Currently Supported Android ROMs
- LineageOS 17.1

## Currently Supported Android Recoveries
- TWRP 9.0 based recoveries

## Instructions to sync device trees
```
$ cd path-to-android-source-tree
$ mkdir .repo/local_manifests
$ wget [Raw URL of the corresponding manifest] -O .repo/local_manifests/ulysse.xml
$ repo sync
```

## Notes about choosing target device
- `ugglite`: Only for Lite variant.
- `ugg`: Only for Prime variant.
- `ulysse`: Unified, Usable on both Lite and Prime variants.

## Instructions to build LineageOS 17.1
Follow the instructions on [here](https://wiki.lineageos.org/devices/whyred/build).<br>
(Just need to replace the name `whyred` with the target device name that you want)

## Instructions to build TWRP 9.0 based recoveries (Using OrangeFox as example)
Follow the instructions on [here](https://gitlab.com/OrangeFox/Manifest/-/blob/fox_9.0/README.md).

## Device Pictures
![Xiaomi Redmi Note 5A / Y1 Lite](https://souqcms.s3.amazonaws.com/spring/images/2017/Xiaomi/Redmi-Note-5A-Dual-Sim/4-Redmi-Note-5A-Dual-Sim-Grey.jpg "Xiaomi Redmi Note 5A/Y1 Lite")
