# ansible-openwrt-sysupgrade
Upgrading OpenWrt firmware using Ansible

## Change defaults
Set branch, target, subtarget and device:
```
openwrt_platform: ramips/mt7621
openwrt_device: xiaomi_mi-router-4
openwrt_version: 21.02.0-rc1
```

## Run playbook
Run master playbook:
```
ansible-playbook -i production site.yml
```
