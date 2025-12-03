# Ansible role Ubuntu Surface

This Ansible role installs the Linux Surface kernel and related packages on Ubuntu or Debian systems, enabling full hardware support for Microsoft Surface devices.
It configures the official Surface Linux repository, installs the custom kernel, updates GRUB, and handles SecureBoot enrollment support.

## Features


- Installs required dependencies (wget, gpg)

- Adds the official Linux Surface GPG key

- Configures the Surface Linux APT repository

- Installs:

  - linux-image-surface

  - linux-headers-surface

  - libwacom-surface

  - iptsd (Intel Precise Touch & Stylus Daemon)

- Installs linux-surface-secureboot-mok for SecureBoot support

- Updates GRUB automatically