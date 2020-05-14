# ebs-nvme-mapping

This repo contains scripts for mapping nvme disks to presistent device names


# Pre-requisits
      
      Python 2.7

# Setup

Copy 70-ec2-nvme-devices.rules to /etc/udev with 644 permission

Copy ebsnvme-id to /sbin with 755 permission

Reboot the server