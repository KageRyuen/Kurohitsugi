# Kurohitsugi

This is a linux system lockdown tool.
*Work in progress*

## Introduction

The planned features are the following:
  - Interactive mode in terminal
  - Easy (temporary or permanent) sandboxing via the interactive frontend, using firejail
  - SSH lockdown
  - Full internet lockdown (firewall rules, network related processes, etc.)
  - Interactive creation of LUKS2 encrypted virtual disk images, see this [guide](https://github.com/KageRyuen/LUKS2-DiskImageGuide)
  - Scanning for rootkits and RATs interactively, which employs rkhunter and chkrootkit, as well as ClamAV (if selected)
  - Lockdown (and/or poweroff) of USB ports
  - Emergency lockdown, internet and USB ports via one command in the terminal
  - Revert option for each lockdown feature
