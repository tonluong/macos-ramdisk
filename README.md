# macos-ramdisk
Create Ramdisk on macOS


## usage
```bash
# creates 1GB HFS ramdisk under /Volumes/ram
macos.ramdisk.hfs

# creates 1GB APFS ramdisk under /Volumes/ram
macos.ramdisk.apfs


# creates 2GB HFS ramdisk under /Volumes/ramdisk
macos.ramdisk.hfs 2048 ramdisk

# --- same as above
macos.ramdisk.hfs ramdisk 2048


# creates 2GB APFS ramdisk under /Voumes/ramdisk
macos.ramdisk.apfs 2048 ramdisk

# --- same as above
macos.ramdisk.apfs ramdisk 2048
```