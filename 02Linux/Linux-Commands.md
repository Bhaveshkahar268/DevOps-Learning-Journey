# 🐧 Linux Commands Revision Sheet (50+ Important Commands)

Linux commands are used to perform file management, process management, networking, system administration, package management, and many other daily tasks in Linux operating systems.

---

| Command | Description |
| -------------------------- | ----------------------------------- |
| `pwd` | Show current working directory |
| `ls` | List files and directories |
| `ls -l` | Detailed list format |
| `ls -a` | Show hidden files |
| `cd dir` | Change directory |
| `cd ..` | Move one directory back |
| `cd ~` | Go to home directory |
| `mkdir dir` | Create new directory |
| `rmdir dir` | Remove empty directory |
| `touch file.txt` | Create empty file |
| `cat file.txt` | Display file content |
| `nano file.txt` | Open file in Nano editor |
| `vim file.txt` | Open file in Vim editor |
| `cp file1 file2` | Copy file |
| `cp -r dir1 dir2` | Copy directory recursively |
| `mv old new` | Move or rename file |
| `rm file.txt` | Delete file |
| `rm -r dir` | Delete directory recursively |
| `rm -rf dir` | Force delete directory |
| `clear` | Clear terminal screen |
| `history` | Show command history |
| `man ls` | View command manual |
| `echo "Hello"` | Print output |
| `whoami` | Display current user |
| `uname -a` | Show system information |
| `hostname` | Display system hostname |
| `date` | Show current date and time |
| `cal` | Display calendar |
| `df -h` | Show disk usage |
| `du -sh dir` | Show directory size |
| `free -h` | Display memory usage |
| `top` | Show running processes |
| `htop` | Interactive process viewer |
| `ps` | Display current processes |
| `ps -ef` | Detailed process list |
| `kill PID` | Kill process |
| `kill -9 PID` | Force kill process |
| `chmod 755 file` | Change permissions |
| `chown user file` | Change ownership |
| `grep word file.txt` | Search text |
| `find . -name file.txt` | Find file |
| `locate file.txt` | Locate files quickly |
| `head file.txt` | First 10 lines |
| `tail file.txt` | Last 10 lines |
| `tail -f log.txt` | Live log monitoring |
| `sort file.txt` | Sort file |
| `wc file.txt` | Count words, lines & characters |
| `zip file.zip file.txt` | Compress file |
| `unzip file.zip` | Extract ZIP archive |
| `tar -cvf file.tar dir` | Create tar archive |
| `tar -xvf file.tar` | Extract tar archive |
| `ping google.com` | Test connectivity |
| `ifconfig` | Display network interfaces *(older systems)* |
| `ip a` | Show IP address information |
| `wget URL` | Download file |
| `curl URL` | Transfer data |
| `ssh user@ip` | Remote login |
| `scp file user@ip:path` | Secure file copy |
| `sudo command` | Run command as administrator |
| `apt update` | Update package list |
| `apt install package` | Install package |
| `systemctl status service` | Service status |
| `systemctl start service` | Start service |
| `systemctl stop service` | Stop service |
| `systemctl restart service` | Restart service |
| `reboot` | Restart Linux |
| `shutdown now` | Shutdown immediately |

---

# 💡 Frequently Used Commands

These commands are used almost every day by Linux Administrators and DevOps Engineers:

- `pwd`
- `ls -la`
- `cd`
- `mkdir`
- `cp`
- `mv`
- `rm`
- `grep`
- `find`
- `tail -f`
- `top`
- `ps -ef`
- `chmod`
- `chown`
- `systemctl`
- `ssh`
- `scp`

---

# 🎯 Best Practices

✅ Always use `sudo` carefully.

✅ Verify the path before using `rm -rf`.

✅ Prefer `ip a` over `ifconfig` on modern Linux systems.

✅ Use `man` pages to understand commands.

✅ Monitor logs using `tail -f`.

✅ Keep your system updated using package managers.

---

# 🚀 Quick Revision

Linux commands can be grouped into:

- 📁 File & Directory Management
- 👤 User Management
- 🔐 Permissions
- ⚙ Process Management
- 🌐 Networking
- 📦 Package Management
- 📜 System Administration
