# CMD Commands Cheat Sheet

This document provides a list of commonly used Command Prompt (CMD) commands along with their descriptions. CMD is a powerful tool for managing files, directories, networks, and system configurations on Windows systems.

---

## **1. Basic CMD Commands**
| **Command**       | **Description**                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| `dir`             | Displays a list of files and folders in the current directory.                                   |
| `cd`              | Changes the directory. (`cd foldername` or `cd ..` to go up one level).                         |
| `cls`             | Clears the Command Prompt screen.                                                              |
| `exit`            | Closes the Command Prompt window.                                                              |
| `help`            | Lists all available CMD commands.                                                              |
| `echo`            | Displays a message or turns the echo feature on/off.                                           |
| `path`            | Displays or sets the system PATH variable.                                                     |

---

## **2. File and Folder Management**
| **Command**       | **Description**                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| `mkdir` or `md`   | Creates a new directory. (`mkdir foldername`)                                                   |
| `rmdir` or `rd`   | Removes an empty directory.                                                                     |
| `del`             | Deletes one or more files. (`del filename`)                                                    |
| `copy`            | Copies files from one location to another.                                                     |
| `xcopy`           | Copies files and directories, including subdirectories.                                        |
| `move`            | Moves files from one location to another.                                                      |
| `ren` or `rename` | Renames a file or folder.                                                                       |

---

## **3. Viewing and Editing Files**
| **Command**       | **Description**                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| `type`            | Displays the contents of a text file.                                                          |
| `more`            | Displays the contents of a file, one screen at a time.                                         |
| `fc`              | Compares two files and displays the differences.                                               |

---

## **4. Disk Management**
| **Command**       | **Description**                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| `chkdsk`          | Checks the disk for errors. (`chkdsk C:`)                                                      |
| `diskpart`        | Opens the Disk Partition Manager.                                                              |
| `format`          | Formats a disk or partition.                                                                  |
| `vol`             | Displays the volume label and serial number of a disk.                                        |
| `label`           | Changes or creates a disk volume label.                                                       |
| `diskcopy`        | Copies the contents of one floppy disk to another.                                             |

---

## **5. Network Commands**
| **Command**       | **Description**                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| `ping`            | Tests the connectivity to another device or website. (`ping google.com`)                       |
| `ipconfig`        | Displays network configuration details like IP address, subnet mask, and gateway.              |
| `nslookup`        | Checks DNS information.                                                                        |
| `tracert`         | Traces the route data takes to reach a network destination.                                     |
| `netstat`         | Displays active network connections and ports in use.                                          |
| `arp`             | Displays or modifies the ARP table.                                                            |
| `net use`         | Connects or disconnects from a shared network resource.                                        |
| `net user`        | Manages user accounts on the system.                                                           |

---

## **6. System Information and Control**
| **Command**       | **Description**                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| `systeminfo`      | Displays detailed system information, including OS, RAM, and CPU.                              |
| `tasklist`        | Displays a list of running processes.                                                          |
| `taskkill`        | Terminates a process by its name or PID.                                                       |
| `set`             | Displays or sets environment variables.                                                       |
| `time`            | Displays or sets the system time.                                                              |
| `date`            | Displays or sets the system date.                                                              |
| `shutdown`        | Shuts down or restarts the computer. (`shutdown /s` or `shutdown /r`)                          |
| `cls`             | Clears the command window.                                                                     |

---

## **7. Troubleshooting and Diagnostics**
| **Command**       | **Description**                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| `sfc`             | Scans and repairs corrupted system files.                                                      |
| `driverquery`     | Displays a list of all installed drivers on the system.                                        |
| `pathping`        | Combines `ping` and `tracert` for advanced diagnostics.                                        |
| `powercfg`        | Manages power settings.                                                                        |
| `taskmgr`         | Opens the Task Manager.                                                                        |
| `msconfig`        | Opens the System Configuration tool.                                                           |

---

## **8. User and Group Management**
| **Command**       | **Description**                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| `net user`        | Creates, deletes, or lists user accounts.                                                      |
| `whoami`          | Displays the current logged-in user.                                                           |
| `net localgroup`  | Manages local user groups.                                                                     |

---

## **9. File Compression and Extraction**
| **Command**       | **Description**                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| `compact`         | Displays or alters the compression of files or directories.                                    |
| `expand`          | Extracts files from compressed `.cab` files.                                                  |

---

## **10. Advanced Commands**
| **Command**       | **Description**                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| `reg`             | Manipulates the Windows registry.                                                             |
| `schtasks`        | Creates, deletes, or manages scheduled tasks.                                                 |
| `cipher`          | Encrypts or decrypts files/folders on NTFS partitions.                                        |
| `wmic`            | Performs WMI (Windows Management Instrumentation) tasks.                                      |
| `attrib`          | Displays or changes file attributes (e.g., hidden, read-only).                                |

---

## **11. Development and Debugging**
| **Command**       | **Description**                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| `notepad`         | Opens the Notepad editor.                                                                      |
| `edit`            | Opens a basic text editor (older versions of Windows).                                         |
| `start`           | Opens files or launches programs.                                                             |

---

## **12. Keyboard Shortcuts in CMD**
| **Shortcut**      | **Description**                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| `Ctrl + C`        | Stops a running command.                                                                       |
| `Ctrl + V`        | Paste text into the command line.                                                              |
| `Arrow Keys`      | Navigate through previous commands.                                                            |
| `Tab`             | Auto-complete folder or file names.                                                           |

---

## **Tips for Using CMD**
- Run CMD as an **administrator** when you need elevated permissions (`Right-click > Run as Administrator`).
- Use the `/help` flag with any command for detailed instructions (e.g., `ping /help`).
- To navigate faster, drag and drop folders into CMD to paste their full path.

