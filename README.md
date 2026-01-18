# updated-promomox-ubuntu-vm-template

This is updated notes/guide to create vm template using ubuntu cloud image

## Steps 1: In Proxmox, click on ```Create VM```
<img width="646" height="248" alt="image" src="https://github.com/user-attachments/assets/d818e96f-1f15-4164-8265-31e4301d3d06" />

### In OS Tab > uncheck ``` Do not use any media```
<img width="672" height="309" alt="image" src="https://github.com/user-attachments/assets/d75d7294-fd1c-469b-b85c-be3d79067da0" />

### In System Tab: 
- Machine:```q35``` 
- BIOS:```OVMF (UEFI)```
- EFI Storage:```local```
- Qemu Agent > Checked
<img width="724" height="379" alt="image" src="https://github.com/user-attachments/assets/91a742e0-dd70-405d-9af8-6c287bf9af96" />

### In Disks Tab, Delete the disk as we will create and attach new disk manually
<img width="639" height="350" alt="image" src="https://github.com/user-attachments/assets/f823f904-7d8f-40a6-a968-f168d8f9e5d5" />

### In CPU Tab, set Cores: ```2```
<img width="647" height="258" alt="image" src="https://github.com/user-attachments/assets/da6de449-10d6-4863-b8a5-84410d4c3803" />

### In Memory Tab, Set MiB: ```2028```
<img width="631" height="245" alt="image" src="https://github.com/user-attachments/assets/bed22af6-5ea1-4b59-ab34-96e44eb111fa" />

### In Network Tab, let default value.

### In Confirm Tab, Start after created: ```uncheck```. Then click on Finish
<img width="433" height="205" alt="image" src="https://github.com/user-attachments/assets/d213bf9e-7f8e-4b05-9d6e-7e7f6a4d57e7" />



