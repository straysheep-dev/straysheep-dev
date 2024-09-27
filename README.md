## [straysheep.dev](https://straysheep.dev) 🌐

Hi, I'm straysheep-dev. 👋

⚔️ I'm here learning security from an offensive perspective and documenting things in a useful way as I go.

🛡️ I also focus on building defensive (or "visibility") tools, and configuration templates learned from applying offensive techniques to systems.

### Certifications

![Static Badge](https://img.shields.io/badge/OSCP-orange) ![Static Badge](https://img.shields.io/badge/OSWP-blue) ![Static Badge](https://img.shields.io/badge/PNPT-purple) ![Static Badge](https://img.shields.io/badge/eCPPT-orange) ![Static Badge](https://img.shields.io/badge/eCMAP-blue) ![Static Badge](https://img.shields.io/badge/eJPT-red)

## Connect

| ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=github) | **straysheep-dev** |
| --- | --- |
| ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=gitlab) | **straysheep-dev** |
| ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=discord) | **straysheep_dev** |
| ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=hackthebox&logoColor=green) | **straysheepdev** |
| ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=tryhackme&logoColor=red) | **straysheep.dev** |

## Projects

⬇️ Core projects. ➡️ My [guides and utilities](https://straysheep.dev/#__tabbed_1_3). ➡️ My [blog](https://straysheep.dev/blog/) illustrating various topics.

## [linux-configs](https://github.com/straysheep-dev/linux-configs) ![Static Badge](https://img.shields.io/badge/Ubuntu-orange?logo=ubuntu&logoColor=white) ![Static Badge](https://img.shields.io/badge/Fedora-white?logo=fedora) ![Static Badge](https://img.shields.io/badge/Debian-white?logo=debian&logoColor=red) ![Static Badge](https://img.shields.io/badge/pfSense-blue?logo=pfsense&logoColor=white) ![Static Badge](https://img.shields.io/badge/OpenWRT-white?logo=openwrt) ![Static Badge](https://img.shields.io/badge/MIT-red) ![Static Badge](https://img.shields.io/badge/GPL--3.0-green) ![Static Badge](https://img.shields.io/badge/BSD--3--Clause-blue)

Utilities and configuration files accompanied by guides, focusing on security. These include web browsers, GPG, SSH, DNS, VPN's, shell profiles, hypervisors, tools to parse and summarize system processes, network activity, auditd logs, strings in project files (based on bstrings) and more.


## [windows-configs](https://github.com/straysheep-dev/windows-configs) ![Static Badge](https://img.shields.io/badge/Windows-blue?logo=windows) ![Static Badge](https://img.shields.io/badge/PowerShell-white?style=flat&color=blue) ![Static Badge](https://img.shields.io/badge/MIT-red) ![Static Badge](https://img.shields.io/badge/CC_BY--SA_4.0-orange)

PowerShell modules and scripts used to configure windows or automate tasks. Plus an extensive walkthrough of Windows specific items such as Hyper-V usage, Windows Sandbox, WSL + USB, logging & monitoring, and more.


## [ansible-configs](https://github.com/straysheep-dev/ansible-configs) ![Static Badge](https://img.shields.io/badge/Ansible-white?&logo=ansible&logoColor=black) ![Static Badge](https://img.shields.io/badge/MIT-red) ![Static Badge](https://img.shields.io/badge/GPL--3.0-green) ![Static Badge](https://img.shields.io/badge/BSD--3--Clause-blue)

A collection of ansible roles, with guidance on writing, debugging, and linting ansible code. This includes secrets management, testing plays, and more. The roles are meant to be mixed and used however needed, and offer conditional options for deployment. The main `playbook.yml` file is commented to help you get started.


## [vagrant-configs](https://github.com/straysheep-dev/vagrant-configs) ![Static Badge](https://img.shields.io/badge/Vagrant-white?&logo=vagrant&logoColor=blue) ![Static Badge](https://img.shields.io/badge/MIT-red)

How vagrant works, and everything needed to get started using it with security in mind. Includes a sample Vagrantfile for Kali on Hyper-V and VirtualBox showing what provider settings you may want to use. Quirks of Hyper-V and how to resolve them are covered. Lastly, resources to be aware of for building a home lab are linked.


## [terraform-configs](https://github.com/straysheep-dev/terraform-configs) ![Static Badge](https://img.shields.io/badge/Terraform-white?&logo=terraform) ![Static Badge](https://img.shields.io/badge/MIT-red)

Ready to use terraform templates, and an easy to follow guide to go from installing, to deploying resources. Also includes guidance on fixing partial deployments, secrets management, and how to generate an ansible inventory from your deployed resources.


## [alert-service](https://github.com/straysheep-dev/alert-service) ![Static Badge](https://img.shields.io/badge/Windows-blue?&logo=windows) ![Static Badge](https://img.shields.io/badge/Linux-white?&logo=linux&logoColor=black) ![Static Badge](https://img.shields.io/badge/PowerShell-white?style=flat&color=blue) ![Static Badge](https://img.shields.io/badge/Python3-blue?&logo=python&logoColor=gold) ![Static Badge](https://img.shields.io/badge/MIT-red)

Webhook based alerting (Slack, Discord...) for events, account access, honey files, etc. It's meant as a follow up to [IppSec's video on this topic](https://www.youtube.com/watch?v=J9owPmgmfvo&t=1545s), with ready-to-use examples of sending an alert on both Windows and Linux using [cyber deception](https://github.com/strandjs/IntroLabs/blob/master/IntroClassFiles/navigation.md) to catch malicious behavior early.


## Featured Tools

| COMPONENTS | DESCRIPTION | LINKS |
| ---: | :--- | --- |
| ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=wireguard) ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=ansible&logoColor=black) ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=terraform) ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=linux) | Deploy a Wireguard server with interface monitoring | [Ansible](https://github.com/straysheep-dev/ansible-configs/tree/main/build_wireguard_server) + [Terraform](https://github.com/straysheep-dev/terraform-configs) |
| ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=wireguard) ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=ansible&logoColor=black) ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=terraform) ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=linux) | Deploy a Tailscale node | [Ansible](https://github.com/straysheep-dev/ansible-configs/tree/main/build_tailscale_node) + [Terraform](https://github.com/straysheep-dev/terraform-configs) |
| ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=pfsense&logoColor=blue) | pfSense administration, lab, usage guide | [Guide](https://straysheep.dev/blog/2024/05/02/pfsense-administration/) |
| ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=vmware) ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=ubuntu) | VMware kernel module signing for SecureBoot on Ubuntu | [Bash](https://github.com/straysheep-dev/linux-configs/blob/main/hypervisors/vmware/vmware-sign-modules.sh) |
| ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=linux) ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=ansible&logoColor=black) | Deploy auditd + laurel | [Ansible](https://github.com/straysheep-dev/ansible-configs/tree/main/install_auditd), [Bash](https://github.com/straysheep-dev/setup-auditd) |
| ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=linux) ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=ansible&logoColor=black) | Deploy unbound DNS resolver with DNS over TLS + logging | [Ansible](https://github.com/straysheep-dev/ansible-configs/tree/main/install_unbound), [Bash](https://github.com/straysheep-dev/linux-configs/tree/main/dns)  |
| ![Static Badge](https://img.shields.io/badge/Win-white?style=flat&color=blue) ![Static Badge](https://img.shields.io/badge/-gray?style=social&logo=linux) | Hyper-V Enhanced Session Linux guest tools (for manual installation) | [Ansible](https://github.com/straysheep-dev/ansible-configs/tree/main/hyperv_guest_tools), [Fork](https://github.com/straysheep-dev/linux-vm-tools/blob/master/ubuntu/22.04/install.sh) |
| ![Static Badge](https://img.shields.io/badge/Win-white?style=flat&color=blue) ![Static Badge](https://img.shields.io/badge/%3E__-white?style=flat&color=blue) | Deploy and manage OpenSSH Server on Windows | [PS Module](https://github.com/straysheep-dev/windows-configs/blob/main/Manage-OpenSSHServer.ps1) |
| ![Static Badge](https://img.shields.io/badge/Win-white?style=flat&color=blue) ![Static Badge](https://img.shields.io/badge/%3E__-white?style=flat&color=blue) | Deploy and manage Sysinternals + Sysmon rules on Windows | [PS Script](https://github.com/straysheep-dev/windows-configs/blob/main/Manage-Sysinternals.ps1) |
| ![Static Badge](https://img.shields.io/badge/Win-white?style=flat&color=blue) ![Static Badge](https://img.shields.io/badge/%3E__-white?style=flat&color=blue) | Windows Sandbox configuration files and startup scripts | [WSB Files](https://github.com/straysheep-dev/windows-configs#windows-sandbox) |

### I’m currently working on...

- 🎯 Other pentesting certifications
- 🏗️ Git, infrastructure, automation
- 🛠️ Building utilites for everyday use
