# Hi, I'm Nogunix

![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Fedora](https://img.shields.io/badge/Fedora-51A2DA?logo=fedora&logoColor=white)
![Red Hat](https://img.shields.io/badge/Red%20Hat-EE0000?logo=redhat&logoColor=white)
![OpenShift](https://img.shields.io/badge/OpenShift-C9190B?logo=redhatopenshift&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-1A1918?logo=ansible&logoColor=white)
![OpenTofu](https://img.shields.io/badge/OpenTofu-FFDA18?logo=opentofu&logoColor=black)

I work across the whole Linux stack — from the kernel up to the platforms built on it.

- **Kernel** — kernel internals, crash dump analysis (kdump / vmcore), device and power management
- **RHEL / Fedora** — distribution-level troubleshooting and OSS packaging; Fedora Copr maintainer, responsible for user-facing packages ([My Copr repos](https://copr.fedorainfracloud.org/coprs/nogunix/))
- **OpenShift** — cluster deployment and automation, OpenShift Virtualization (CNV), upgrade and compatibility analysis
- **Projects** — what I build and maintain in my personal capacity:
  - [usb-wakeup-blocker](https://github.com/nogunix/usb-wakeup-blocker) — a script and systemd service to precisely control which devices can wake a Linux system from sleep
  - [linux-japanese-font-fix](https://github.com/nogunix/linux-japanese-font-fix) — a Fontconfig setting that fixes common Japanese font rendering issues (the "Chinese font problem") on non-Japanese locales
  - [sno-auto-builder](https://github.com/nogunix/sno-auto-builder) — automated OpenShift Single Node (SNO) deployment on Fedora / CentOS Stream / Ubuntu + libvirt using Ansible and OpenTofu
  - [janus](https://github.com/nogunix/janus) — Claude Code plugin: an OpenShift/RHEL/CNV research & investigation pipeline
  - [fedora-vm-builder](https://github.com/nogunix/fedora-vm-builder) — Ansible + OpenTofu builder for disposable Fedora VMs with kdump and kernel debuginfo pre-configured


## Philosophy

The name **Nogunix** reflects my appreciation for the Unix philosophy:  
*"Write programs that do one thing and do it well. Write programs to work together. Handle text streams, because that is a universal interface."*  

I try to apply this principle in my projects—keeping them simple, modular, and composable.


## Disclaimer  
This is my personal profile. All projects listed here are created and maintained in my personal capacity, and have no relation to my employer's business or confidential information.
