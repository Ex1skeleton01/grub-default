# grub-default

# 1 change GRUB_DEFAULT
```
sudo nano /etc/default/grub
```
u can see GRUB_DEFAULT=1 change this 

# 2 update GRUB
fedora
```
sudo grub2-mkconfig -o /boot/grub2/grub.cfg
```
for UEFI system
```
sudo grub2-mkconfig -o /boot/efi/EFI/fedora/grub.cfg
```

# command update that may be used frequently
```
sudo update-grub
```
