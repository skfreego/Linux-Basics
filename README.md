# Linux-Basics

pwd        # Print current directory
ls         # List files
cd         # Change directory
mkdir      # Make directory
touch      # Create files

File Operations

View/Edit Files 
cat, less, head, tail, nano, vim

Copy/Move/Delete
cp, mv, rm

Permissions & Users

:Understand File Permissions- ls -l
:Change Permissions- chmod, chown
:User Management- adduser, passwd, su, sudo

Package Management
:Ubuntu uses apt

sudo apt upgrade
sudo apt update
sudo apt install <package>
sudo apt remove <package>


Process and System Monitoring
:System resources- top, htop, free, df , du
:Manage Processes- ps, kill, nice

Scheduled Tasks
: cron and crontab usage

crontab -e

Shell Scripting
:bash basics- variables, loops, if-else, functions

Example
#!/bin/bash
for file in *.txt; do
  echo "File: $file"
done

Networking & SSH
:IP config- ip, ifconfig, ping
:connect via ssh- ssh user@host
:Port checking- netstat, ss, nc

Systemd & Services
:Manage services
systemctl start/stop/status <service>

Logs & Troubleshooting
journalctl, dmesg, /var/log/syslog, etc

Security
:UFW (Uncomplicated Firewall)- sudo ufw enable
Fail2Ban, AppArmor basics

Advanced Shell & CLI tools
awk, sed, grep, cut, xargs, find
Chaining & piping commands: |, &&, ||
