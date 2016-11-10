# mountimg tool

mountimg is a simple script to mount a specific partition from a disk image
as a loop device.

## Usage:

    $ sudo mountimg <disk_image_file> <partition_number> <mountpoint> <mountoptions>

## Example:

    $ sudo mountimg mydisk.img 1 /mnt/mydiskp1 -t vfat -o ro,codepage=866,iocharset=utf-8
