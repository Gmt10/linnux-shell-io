# Install Software in a Linux Distribution

## Project Overview
Practiced managing software applications in a Linux environment using command-line package managers (`apt`) to install, update, and remove tools.

## Key Skills Demonstrated
* Updating local package repository indexes before installing software
* Installing and uninstalling command-line utilities via `sudo apt`
* Verifying software installations and checking package status

## Lab Tasks & Commands
### 1. Updating Package Lists
Refreshed the local package index to ensure access to the latest software versions and security patches.
```bash
sudo apt update
```

### 2. Installing and Verifying Applications
Installed required utilities and confirmed they were properly configured on the system.
```bash
sudo apt install suricata -y
which suricata
```

### 3. Removing Unnecessary Packages
Cleaned up unused software packages to maintain a secure, minimal system footprint.
```bash
sudo apt remove suricata -y
```

## Outcome
Successfully installed, verified, and removed software packages from the Linux command line using standard package management workflows.
