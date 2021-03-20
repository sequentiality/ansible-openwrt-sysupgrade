# ansible-openwrt-sysupgrade
Upgrading OpenWrt firmware using Ansible

## Change defaults
Set branch, target, subtarget and device:
```
openwrt_branch: snapshots
# openwrt_branch: releases/19.07.7
openwrt_target: ramips
openwrt_subtarget: mt7621
openwrt_device: xiaomi_mi-router-4
```

## Run playbook
Run master playbook:
```
ansible-playbook -i production site.yml
```
