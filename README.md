# Nitrux Plymouth Theme

This is the repository for the Plymouth theme used in Nitrux.

# Requirements
- Plymouth.

# BGRT

The package includes a BGRT theme that preserves the firmware logo and displays the Nitrux logo when firmware graphics are unavailable. It is selected by default and its assets are included in the initramfs.

To select it manually and rebuild the initramfs:

    sudo plymouth-set-default-theme -R bgrt

# Issues

If you find problems with the contents of this repository please create an issue.

©2018 Nitrux Latinoamericana S.C.
