# ovirt
Ovirt / RHV automation scripts

This project is intended to automate the storage migration from one storage domain to another.

The below command will move all discs from <VM_NAME> to a new storage domain <NEW_STORAGE_DOMAIN>:

```
python move_sd.py <NEW_STORAGE_DOMAIN> <VM_NAME>
```
