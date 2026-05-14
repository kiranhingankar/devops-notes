# 🐧 Linux Commands Cheat Sheet

A quick reference guide for essential Linux commands used in DevOps and system administration.

---

# 📁 File System Commands

| Command | Usage |
|----------|--------|
| `ls -la` | List all files (including hidden) with detailed information |
| `pwd` | Show current working directory |
| `cd <dir>` | Change directory |
| `cd ..` | Move one directory back |
| `mkdir <dir>` | Create a new directory |
| `rm -rf <dir/file>` | Remove files/directories forcefully |
| `cp -r <src> <dest>` | Copy directories recursively |
| `mv <src> <dest>` | Move or rename files |
| `find / -name <file>` | Search for a file by name |
| `du -sh *` | Show size of files/directories |
| `df -h` | Display disk space usage |

---

# ⚙️ Process Management

| Command | Usage |
|----------|--------|
| `ps aux` | View all running processes |
| `top` | Real-time process monitoring |
| `htop` | Interactive process viewer |
| `kill <PID>` | Terminate a process |
| `kill -9 <PID>` | Force kill a process |
| `pkill <name>` | Kill process by name |
| `nice -n 10 <cmd>` | Start process with priority |
| `renice <priority> -p <PID>` | Change process priority |
| `jobs` | List background jobs |
| `bg` / `fg` | Move jobs to background/foreground |

---

# 🌐 Networking & Troubleshooting

| Command | Usage |
|----------|--------|
| `ping <host>` | Check network connectivity |
| `ip addr` | Show IP addresses and interfaces |
| `ss -tulnp` | Show open ports and listening services |
| `netstat -tulnp` | Display network connections and ports |
| `curl <url>` | Test HTTP requests/APIs |
| `wget <url>` | Download files from internet |
| `dig <domain>` | Perform DNS lookup |
| `nslookup <domain>` | Query DNS records |
| `traceroute <host>` | Trace network path to host |
| `hostname -I` | Display system IP address |

---

# 📄 Logs & System Information

| Command | Usage |
|----------|--------|
| `cat <file>` | Display file contents |
| `less <file>` | Read large files page by page |
| `tail -f <file>` | Monitor logs in real time |
| `head <file>` | Show first lines of a file |
| `grep "text" <file>` | Search for text inside files |
| `uptime` | Show system uptime and load |
| `whoami` | Display current logged-in user |
| `uname -a` | Show system and kernel information |

---

# 💡 Useful DevOps Tip

```bash
tail -f application.log | grep "ERROR"
