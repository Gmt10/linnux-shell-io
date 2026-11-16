# Manage File Permissions in Linux

## Project Overview
Audited and modified file and directory permissions in a Linux environment to enforce least-privilege access controls.

## Key Skills Demonstrated
* Inspecting existing read, write, and execute permissions with `ls -la`
* Modifying user, group, and other permissions using `chmod`
* Updating file ownership and group assignments with `chown`

## Lab Tasks & Commands
### 1. Auditing Directory Permissions
Checked permission strings and ownership across sensitive project files and directories.
```bash
ls -la /home/analyst/projects
```

### 2. Restricting Unauthorized Access
Removed write and execute permissions from unauthorized users and groups to secure sensitive files.
```bash
chmod g-w,o-rwx project_k.txt
chmod u+x update_script.sh
```

## Outcome
Successfully identified overly permissive file settings and applied principle-of-least-privilege controls using `chmod`.
