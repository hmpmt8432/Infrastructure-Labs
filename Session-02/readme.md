# Week 02 - Linux Ubuntu and SSH

## What I Built

Installed Ubuntu Server 24.04 on a VirtualBox VM and connected to it via SSH from my host machine.

## Virtual Machine Server Specs
- RAM 4096 MB
- Disk 25 GB
- OS: Ubuntu Server 24.04
- Network Bridged Adapter
- Hostname 'ubuntu-lab'
- username 'labuser'

## Server IP Address

- IP: '192.168.0.58'

## Commands I Ran

Updating the Server
```
sudo apt update
sudo apt upgrade
```

Check disk space
```
df -h
```

Check memory use
```
free -h
```
Connected via SSH
```
ssh labuser@192.168.0.58
```

## Observations
1. The server has 15 GB free space after installation
2. RAM usage was at 500 MB at idle
3. The SSH connection was instant after first connection was established
4. SSH has remembered the VM as trusted connection after confirming first connection

## Session Checklist
-[x] Ubuntu Server installed
-[ ] SSH access confirmed

## Problems

See 'troubleshooting.md' for the first issue and resolution
