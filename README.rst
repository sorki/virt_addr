virt_addr
=========

Get IP address of a virtual machine running in kvm via libvirt.
This works only if your setup is using NAT, not with bridged networks.

Requires:
 - python
 - lxml
 - libvirt

Usage:
 - virt_addr vm_name
 - virt_addr --system vm_name
