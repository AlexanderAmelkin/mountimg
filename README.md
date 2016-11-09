# mountimg

mountimg is a simple script to mount a specific partition from a disk image
as a loop device.

usage:

    $ sudo mountimg <disk_image_file> <partition_number> <mountpoint>
    
example:

    $ sudo mountimg mydisk.img 1 /mnt/mydiskp1
