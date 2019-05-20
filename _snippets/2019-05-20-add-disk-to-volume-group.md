---
layout: default
---

# Add Disk to Volume Group

* attach the disk
* fdisk create a partition, with type "8e Linux LVM"
* pvcreate /dev/sdc1   - create the physical volume
* vgdisplay - show existing Volume groups
* vgextend vg_splat /dev/sdc1  - add the disk into the volume group

