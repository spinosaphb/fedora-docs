## Add kernel to grub menu


|Description|Superuser|Command|
|:----------|:-----:|:---|
|Update kernel|Yes|`dnf install kernel`|
|Check installed kernels|Yes|`rpm -q kernel`|
|Add kernel to grub menu|Yes|`kernel-install add <version> /boot/vmlinuz-<version>`|
|Remove kernel from grub menu|Yes|`kernel-install remove <version> /boot/vmlinuz-<version>`|
|Remove kernel|Yes|`dnf remove kernel-<version>`|
