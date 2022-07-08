# ansible-openwrt-sysupgrade
Upgrading OpenWrt firmware using Ansible

## Change defaults
Set platform, device and version:
```
openwrt_platform: ramips/mt7621
openwrt_device: xiaomi_mi-router-4
openwrt_version: 22.03.0-rc5
```

## Run playbook
Run master playbook:
```
ansible-playbook -i production site.yml
ansible-playbook -i production site.yml -t sysupgrade
ansible-playbook -i production site.yml -t bootstrap
```
