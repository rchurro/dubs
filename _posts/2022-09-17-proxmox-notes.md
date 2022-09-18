ran out of space setting up ceph on my 16 GB drives. 

#remove lvm-thin / data in the gui
#lvextend -l +100%FREE /dev/pve/root 
#resize2fs /dev/mapper/pve-roo
