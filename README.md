## D01 - Basic Linux Administration

**Project status:** Completed.

Introduction to the fundamentals of Ubuntu Server 20.04 LTS administration. The project covers initial system setup, user management, networking, text editors, and basic monitoring.


### About the Project

This project is a first hands-on introduction to the Linux operating system. The goal was to manually perform all the steps, from OS installation to task scheduler configuration, that a system administrator typically executes on a new server.

All work was carried out on a virtual machine running **Ubuntu Server 20.04 LTS** without a graphical interface.

### Key Skills

The following technologies and tools were learned and applied during the project:

- **OS:** Ubuntu Server 20.04 LTS
- **Network:** Static IP configuration, DHCP, working with `netplan`
- **Users and Permissions:** `adduser`, `usermod`, `sudo`, groups
- **Text Editors:** VIM, Nano, Joe (search and replace)
- **Monitoring and System:** `top`, `htop`, `fdisk`, `df`, `du`, `ncdu`
- **Logging and Tasks:** System logs (`syslog`, `auth.log`), `cron`
- **SSH:** Basic configuration and security of the `sshd` service

### Completed Tasks

Below is a brief summary of what was done:

1.  **OS Installation and Setup:** Installing Ubuntu Server 20.04, setting the hostname and time zone.
2.  **Network:** Configuring a static IP address, gateway, and DNS via `netplan`.
3.  **Users:** Creating a new user, adding them to the `adm` group, and granting `sudo` privileges.
4.  **Security:** Configuring the `SSHD` service on a non-standard port 2022.
5.  **Working with Text:** Mastering the VIM, Nano, and Joe editors with search and replace practice.
6.  **System Monitoring:** Analyzing CPU, memory, and disk usage using `top`, `htop`, `df`, `du`, `ncdu`.
7.  **Logs and Automation:** Analyzing system logs and configuring `cron` jobs.
