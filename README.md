# The AC66R original CFE backup

## Usage
put the mtd-write and CFE.BIN files on your device

```
chmod 755 mtd-write  
mtd-write -i new_cfe.bin -d pmon  
strings /dev/mtd0ro | grep bl_ver  
mtd-erase -d nvram  
reboot  
```
