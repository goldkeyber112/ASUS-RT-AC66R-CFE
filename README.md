## The AC66R original CFE backup

## Usage

chmod 755 mtd-write  
mtd-write -i new_cfe.bin -d pmon  
strings /dev/mtd0ro | grep bl_ver  
mtd-erase -d nvram  
reboot  
