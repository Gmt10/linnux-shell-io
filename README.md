
# Linux Shell Input and Output Analysis

## Project Overview
Explored how the Bash shell handles standard input, standard output, and error messages using command-line utilities in a Linux environment.

## Key Skills Demonstrated
* Navigating directories and inspecting file contents in Bash
* Redirecting standard output (`>`) and appending output (`>>`) to files
* Analyzing command-line error messages and permissions

## Lab Tasks & Commands
### 1. Redirecting Output with `echo`
Used the `echo` command to write and append text strings directly into log files.
```bash
echo "System check complete" > status.txt
echo "No errors found" >> status.txt
cat status.txt
```

### 2. Inspecting Error Messages
Tested commands against restricted or missing files to examine standard error (`stderr`) responses and troubleshoot permissions.
```bash
ls -la /restricted_directory
```

## Outcome
Successfully managed file creation, text redirection, and command troubleshooting within the Bash shell.
