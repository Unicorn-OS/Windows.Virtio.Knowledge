# Boot Disk on Virtio
sch: https://www.google.com/search?q=windows+virtio+drivers+on+boot

Answer: https://superuser.com/questions/1057959/windows-10-in-kvm-change-boot-disk-to-virtio


[quote](https://www.reddit.com/r/VFIO/comments/13x9ibs/comment/jmg81ck/):
>Ultimately you need to convince the Windows bootloader to actually load the virtio drivers and boot from the new device. The amount of magic or luck that requires is uncertain.
>
>https://superuser.com/questions/1057959/windows-10-in-kvm-change-boot-disk-to-virtio
>
>Note that it is also possible to load the virtio drivers from (SATA) CDROM during Windows installation (meaning you could start with a virtio-scsi boot disk and not need to switch later).
>
>Another possibility: the switch between SATA and SCSI may be changing the boot device path, and the Windows bootloader may be failing to autodetect that.
