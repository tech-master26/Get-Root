# Get-Root

[![Whatsapp](https://img.shields.io/badge/Chat-On%20Whatsapp-738BD7.svg?style=for-the-badge)](https://wa.me/8801629744516)

## What's This?

This is a script that allows you to install Root-Access in your termux application without a rooted device

## Updates

**• Updated to Get-Root 22.04**

## Important

**• If you have to use ubuntu in termux with a x86/i\*86 architecture or prefer ubuntu 19.10 you can use this branch -> https://github.com/MFDGaming/ubuntu-in-termux/tree/ubuntu19.10**

**• If you get an error message that says "Fatal Kernel too old" you have to uncomment the line that reads "command+=" -k 4.14.81"" (remove the # that is located in front of the line) in the "startubuntu.sh" file**

### Installation steps

1. Update termux: `apt-get update && apt-get upgrade -y`
2. Install wget: `apt-get install wget -y`
3. Install proot: `apt-get install proot -y`
4. Install git: `apt-get install git -y`
5. Go to HOME folder: `cd ~`
6. Download script: `git clone https://github.com/sirajul26/Get-Root.git`
7. Go to script folder: `cd Get-Root`
8. Give execution permission: `chmod +x install.sh`
9. Run the script: `./install.sh -y`
10. Now just start ubuntu: `./startubuntu.sh`
