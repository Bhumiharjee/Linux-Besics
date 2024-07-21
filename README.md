# Linux-Besics
LINUX Basics is a repository for foundational Linux knowledge. It includes tutorials on essential commands, practical scripts, and configuration tips. Ideal for beginners looking to enhance their Linux skills. Contributions and forks are welcome!

# Linux Basics 🐧

## Overview

Linux is the core component of the operating system that manages hardware resources and provides essential services for all other software.

## Basic Linux Commands

- **`pwd`** (Print Working Directory)
  - **Description:** Shows the current directory path.
  - **Use Case:** Identify your current location in the file system.
  - **Example:** `pwd`

- **`cd`** (Change Directory)
  - **Description:** Changes the current working directory.
  - **Use Case:** Navigate between directories.
  - **Example:** `cd /path/to/directory`

- **`whoami`** 🧑‍💻
  - **Description:** Displays the username associated with the current session.
  - **Use Case:** Confirm the current user logged into the system.
  - **Example:** `whoami`

- **`man`** (Manual Pages) ℹ️
  - **Description:** Displays the manual page for a command.
  - **Use Case:** Access detailed information about commands.
  - **Example:** `man ls` to view the manual for the `ls` command.

- **`ls`**
  - **Description:** Lists directory contents.
  - **Use Case:** Quickly view files and directories within a folder.
  - **Example:** `ls -l`

- **`cp`**
  - **Description:** Copies files or directories.
  - **Use Case:** Duplicate files or directories for backup or modification.
  - **Example:** `cp file1.txt /path/to/destination/`

- **`mv`**
  - **Description:** Moves or renames files or directories.
  - **Use Case:** Organize files by moving them or renaming them.
  - **Example:** `mv oldname.txt newname.txt`

- **`rm`**
  - **Description:** Removes files or directories.
  - **Use Case:** Delete unwanted files or directories.
  - **Example:** `rm file.txt`

- **`chmod`**
  - **Description:** Changes file permissions.
  - **Use Case:** Modify file access permissions.
  - **Example:** `chmod 755 script.sh`

- **`chown`**
  - **Description:** Changes file ownership.
  - **Use Case:** Update file owner and group.
  - **Example:** `chown user:group file.txt`

- **`grep`**
  - **Description:** Searches for text in files.
  - **Use Case:** Find specific strings or patterns within files.
  - **Example:** `grep "error" logfile.log`

- **`find`**
  - **Description:** Searches for files and directories.
  - **Use Case:** Locate files based on various criteria.
  - **Example:** `find /path -name "*.log"`

- **`cat`**
  - **Description:** Concatenates and displays file contents.
  - **Use Case:** View or combine files quickly.
  - **Example:** `cat file.txt`

- **`tail`**
  - **Description:** Displays the end of a file.
  - **Use Case:** Monitor real-time updates in log files.
  - **Example:** `tail -f /var/log/syslog`

- **`top`**
  - **Description:** Displays system processes and resource usage.
  - **Use Case:** Monitor system performance and processes.
  - **Example:** `top`

- **`ps`**
  - **Description:** Displays information about active processes.
  - **Use Case:** View currently running processes.
  - **Example:** `ps aux`

- **`docker`**
  - **Description:** Command-line tool for managing Docker containers.
  - **Use Case:** Manage Docker containers and images.
  - **Example:** `docker run -d nginx`

- **`kubectl`**
  - **Description:** Command-line tool for interacting with Kubernetes clusters.
  - **Use Case:** Manage Kubernetes resources and deployments.
  - **Example:** `kubectl get pods`

- **`ssh`**
  - **Description:** Securely connects to remote machines.
  - **Use Case:** Access and manage remote servers.
  - **Example:** `ssh user@remotehost`

- **`scp`**
  - **Description:** Securely copies files between hosts.
  - **Use Case:** Transfer files securely between local and remote systems.
  - **Example:** `scp file.txt user@remotehost:/path/`

- **`tar`**
  - **Description:** Archives files and directories.
  - **Use Case:** Create or extract compressed archive files.
  - **Example:** `tar -czvf archive.tar.gz files`

- **`wget`**
  - **Description:** Downloads files from the web.
  - **Use Case:** Retrieve files from URLs.
  - **Example:** `wget http://example.com/file.zip`

## Additional Notes on Terminal Commands

- **`touch`**
  - **Purpose:** Creates an empty file.
  - **Example:** `touch new_file.txt`
  - **Output:** (No output if successful)

- **`nano`**
  - **Purpose:** Opens a text editor for creating or editing files.
  - **Example:** `nano textfile.txt`
  - **Output:** (Opens the nano text editor for file editing)

- **`mkdir`**
  - **Purpose:** Creates a new directory.
  - **Example:** `mkdir new_folder`
  - **Output:** (No output if successful)

- **`rm`**
  - **Purpose:** Removes (deletes) files.
  - **Example:** `rm unwanted_file.txt`
  - **Output:** (No output if successful)

## Kernel vs. Operating System

1. **Definition**:
   - **Kernel:** Core component of the OS managing resources and providing essential services.
   - **Operating System:** Collection of software including the kernel, utilities, and user interface.

2. **Scope**:
   - **Kernel:** Manages critical system functions.
   - **Operating System:** Encompasses the kernel and additional system components.

3. **Functionality**:
   - **Kernel:** Handles process, memory, and device management.
   - **Operating System:** Provides a user interface, file management, and networking.

4. **Size and Complexity**:
   - **Kernel:** Smaller, focused on core functionalities.
   - **Operating System:** Larger, including various services and utilities.

5. **User Interaction**:
   - **Kernel:** Indirect interaction via system services.
   - **Operating System:** Directly interacts with users through interfaces and utilities.

---
