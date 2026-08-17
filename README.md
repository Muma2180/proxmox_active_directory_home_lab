# # Proxmox Active Directory Home Lab

## Project Overview

I built an enterprise-style home lab to gain hands-on experience with virtualization, Windows Server administration, Active Directory, DNS, networking, and infrastructure troubleshooting.

The environment uses Proxmox VE as the virtualization platform and Windows Server 2025 to simulate services commonly found in a business IT environment.

## Technologies & Hardware

- Proxmox VE
- Windows Server 2025
- Active Directory Domain Services (AD DS)
- DNS
- Windows Server File Services
- Dell PowerEdge Server
- Dell PowerConnect Managed Switch
- Ethernet Networking
- VirtIO Drivers
- Virtual Machines

## Lab Implementation

During this project, I:

- Installed and configured Proxmox VE
- Created and managed Windows Server virtual machines
- Installed Windows Server 2025
- Configured VirtIO drivers for virtualized hardware
- Configured network interfaces and connectivity
- Deployed Active Directory Domain Services
- Configured DNS services
- Worked with Windows Server file services
- Managed the environment through Proxmox
- Diagnosed driver and network connectivity issues
- Practiced hands-on infrastructure troubleshooting

## Troubleshooting Experience

A major part of this project involved troubleshooting Windows Server networking inside Proxmox.

The Windows Server VM initially did not recognize its virtual Ethernet controller because the required VirtIO network driver was unavailable. I mounted the VirtIO driver ISO, located the appropriate Windows driver, installed it, and verified network connectivity.

This provided practical experience troubleshooting the relationship between virtual hardware, operating-system drivers, and network connectivity.

## Project Evidence

This repository contains screenshots and photographs documenting the lab build, configuration process, virtualization environment, Windows Server setup, networking, and troubleshooting steps.

## Skills Demonstrated

`Proxmox` `Windows Server` `Active Directory` `DNS` `Virtualization` `Networking` `Troubleshooting` `IT Infrastructure`
