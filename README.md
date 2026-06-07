# Operating Systems Basics Lab: Windows, Linux, CLI, and OS Security

## 1. Project Overview
This project goes over the core concepts from TryHackMe's Operating Systems Basics module. The goal is to explain what an operating system does, compare Windows and Linux command line tools, and show how basic system information can be collected from each operating system.

## 2. What an Operating System Does
An operating system is the layer between the user and the computer hardware.

It manages:
- Processes
- Memory
- Files
- Users
- Devices
- Networking
- Security Permissions

Examples:
- Windows
- Linux
- macOS
- Android
- iOS

## 3. GUI vs CLI
| Interface | Meaning | Example |
|---|---|---|
| GUI | Graphical User Interface | Windows desktop, file explorer |
| CLI | Command Line Interface | PowerShell, Command Prompt, Bash |

A GUI is easier for everyday users. A CLI is faster and more powerful for technical tasks.

## 4. Windows CLI Basics
Windows has two common command-line tools:

| Tool | Purpose |
|---|---|
| Command Prompt | Older Windows command line |
| PowerShell | More powerful Windows automation shell |

Useful Windows commands:
| Command | Purpose |
|---|---|
| `whoami` | Shows current user |
| `hostname` | Shows computer name |
| `ipconfig` | Shows network information |
| `dir` | Lists files and folders |
| `cd` | Changes directory |
| `systeminfo` | Shows detailed system information |
| `net user` | Lists local users |
| `tasklist` | Shows running processes |

## 5. Linux CLI Basics
Linux commonly uses a shell such as Bash.

Useful Linux commands:
| Command | Purpose |
|---|---|
| `whoami` | Shows current user |
| `hostname` | Shows computer name |
| `ip addr` | Shows network information |
| `ls` | Lists files and folders |
| `cd` | Changes directory |
| `pwd` | Shows current directory |
| `uname -a` | Shows system/kernel information |
| `ps aux` | Shows running processes |
| `cat /etc/os-release` | Shows Linux distribution information |

## 6. Windows vs Linux Command Comparison
| Task | Windows | Linux |
|---|---|---|
| Show current user | `whoami` | `whoami` |
| Show hostname | `hostname` | `hostname` |
| Show IP info | `ipconfig` | `ip addr` |
| List files | `dir` | `ls` |
| Change directory | `cd` | `cd` |
| Show running processes | `tasklist` | `ps aux` |
| Show system info | `systeminfo` | `uname -a` |
| Read file contents | `type file.txt` | `cat file.txt` |

## 7. Mini Lab: Collect System Information
### Windows
Commands to run:
```powershell
whoami
hostname
ipconfig
systeminfo
tasklist
```

### Linux
Commands to run:
```bash
whoami
hostname
ip addr
uname -a
cat /etc/os-release
ps aux
```

## 8. OS Security Basics
Operating systems include security features to protect users, files, and processes.

Important OS security concepts:
- User accounts
- Passwords
- File permissions
- Administrator/root privileges
- Updates and patches
- Running processes
- Remote access such as SSH

## 9. Cybersecurity Key Takeaways
Cybersecurity professionals need to understand OS knowledge because attackers often target operating systems. 

Security professionals use OS skills to:
- Investigate compromised machines
- Check running processes
- Review users and permissions
- Analyze suspicious files
- Secure remote access
- Collect system information

## 10. What I Learned
From this module, I learned that operating systems control how users, software, and hardware interact with each other. The biggest takeaway is that cybersecurity requires command-line skills. Whether working on Windows, Linux, or someplace else, I need to know how to navigate files, check system information, and understand permissions.

## References
- TryHackMe. "Introduction to Cyber Security." TryHackMe, [https://tryhackme.com/](https://tryhackme.com/module/operating-systems-basics)

## Disclaimer
This project is for educational purposes only. It summarizes concepts learned through TryHackMe and does not include walkthrough answers, flags, or private room solutions.
