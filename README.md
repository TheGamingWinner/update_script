# Windows Update and Package Management Scripts

This project contains PowerShell and Bash scripts for updating Git repositories, pip packages, and checking Windows updates.

## PowerShell Script (git_update.ps1)

### Purpose:
- Checks for Windows updates, updates all Git repositories on the system, and updates pip packages.

### How to Run:
1. Open PowerShell.
2. Navigate to the directory containing `git_update.ps1`.
3. Run the script by typing `.\git_update.ps1`.

### Prerequisites:
- PowerShell must be enabled to run scripts.
- Git and pip must be installed and accessible in the system's PATH.

## Bash Script (update.sh)

### Purpose:
- Updates system packages using Paru, updates Git repositories in a specified directory, updates pip packages, and clears the RAM cache.

### How to Run:
1. Open a terminal.
2. Navigate to the directory containing `update.sh`.
3. Run the script by typing `./update.sh`.

### Prerequisites:
- Ensure Paru is installed for system updates.
- Git and pip must be installed and accessible in the system's PATH.
- jq must be installed for processing JSON data.

## Notes:
- The PowerShell script searches all drives (except DVD drives) for Git repositories to update.
- The Bash script updates Git repositories in a specified directory and pip packages.
- Both scripts may require administrative privileges for certain operations.
- Ensure you have the necessary permissions to execute the scripts and access relevant directories.