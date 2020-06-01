# ovirt
Ovirt / RHV automation scripts

This project is intended to automate the storage migration from one storage domain to another.

In this project I am considering the disks are named after the Virtual Machine, i.e , <VM_NAME>_Disk0 and the VM has no extra snaphots besides the active one.


The below command will move all discs from <VM_NAME> to a new storage domain <NEW_STORAGE_DOMAIN>:

```
python move_sd.py <NEW_STORAGE_DOMAIN> <VM_NAME>
```
