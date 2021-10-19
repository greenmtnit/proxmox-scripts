# proxmox-scripts 

Scripts for managing Proxmox Virtual Environment

Original author: Tim West <tim@greenmtnit.com>

Copyright (C) 2021 Green Mountain IT Solutions, LLC <info@greenmtnit.com>

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA 02111-1307, USA.

## install_scripts
Master script to configure other scripts.

## do_basics
This script runs some basic setup steps for Proxmox, including:
  - Configuring updates
  - Installs commonly used packages
  - Configuring the MOTD
  - Customizing the terminal

## setup_pvemail
Configures sending emails using postfix.

## check_zfs_capacity
Checks zpool capacity and sends an email alert if capacity exceeds a specifed threshold.


## send_boot_alert
Sends an email alert when the system boots.

## setup_fail2ban
Configures fail2ban monitoring for SSH and the Proxmox GUI.

## setup_smartd
Configures disk health monitoring with the smartmontools smartd daemon

## backup
Backs up Proxmox config files

## alert_dataset_not_mounted
Sends an alert if any one ZFS dataset is not mounted.
