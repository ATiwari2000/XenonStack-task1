# XenonStack-task1

# internsctl

## Overview

`internsctl` is a custom Linux command that provides functionalities for CPU information, memory information, user management, and file information with various options.

## Installation

**Clone the repository:**
'''bash
   git clone <repository_url>
'''
**Navigate to the directory:**
  cd internsctl

**Make the script executable:**
chmod +x internsctl

**Optionally, move the script to a directory in your system's PATH (e.g., /usr/local/bin) to make it accessible globally:**
sudo mv internsctl /usr/local/bin/

**Usage**

**Commands:**
cpu: Get CPU information.


internsctl cpu
memory: Get memory information.

internsctl memory

**user: User management**

**Create a new user:**
internsctl user create <username>

**List all regular users:**
internsctl user list


**file: File information.
**
**Get file information:**


**internsctl file getinfo <file-name>
Options:**

--size or -s: Print file size.
internsctl file getinfo --size <file-name>

--permissions or -p: Print file permissions.
internsctl file getinfo --permissions <file-name>

--owner or -o: Print file owner.
internsctl file getinfo --owner <file-name>

--last-modified or -m: Print file last modified.
internsctl file getinfo --last-modified <file-name>

**List users with sudo permissions:**
internsctl user list --sudo-only

**Global Options:**

--help: Show help information.
internsctl --help

--version: Show command version.
internsctl --version


