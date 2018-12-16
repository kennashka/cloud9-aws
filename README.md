# AWS Cloud9 Set-Up

Information/Reminder of How to set-up cloud9 for aws instance.


# Environment Name and Description
* Name
* Description

# Environment Settings
1. Connect and Run in Remote Server (SSH)
* User (ex. Root/Ubuntu)
* Host (example.com)
* Port (defaulted to 22)

#### SSH Configuration

2. Copy and Paste Public SSH Key

```bash
cd  ~/.ssh/
sudo vim authorized_keys 
```
3. Advance Settings
* Environment Path (default: /home/ubuntu/environment )
* Node.js Binary Path (default: /usr/bin/node )
* SSH Jump Host 


# Nodejs Dependency Installation For Ubuntu

* https://nodejs.org/en/download/package-manager/

```bash
curl -sL https://deb.nodesource.com/setup_11.x | sudo -E bash -
sudo apt-get install -y nodejs
```

* https://github.com/nodesource/distributions/blob/master/README.md
