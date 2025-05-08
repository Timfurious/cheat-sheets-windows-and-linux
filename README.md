# 🎯 CTF Post-Exploitation Cheat Sheets</h1>

<p align="center">
🛠️ Fast, reliable, and compact cheat sheets for post-exploitation on Windows 10, Windows 11, and Linux systems.<br>
Perfect for CTFs, red teaming, and pentesting labs after gaining shell access.
</p>

---

## 📁 Included Cheat Sheets

| OS            | File Name                      | Description                                                             |
|---------------|--------------------------------|-------------------------------------------------------------------------|
| 🪟 Windows 10  | `windows10_ctf_cheatsheet.txt` | Post-exploitation commands using legacy PowerShell and WMI             |
| 🪟 Windows 11  | `windows11_ctf_cheatsheet.txt` | Updated PowerShell Core support, modern enumeration & persistence      |
| 🐧 Linux        | `linux_ctf_cheatsheet.txt`     | Bash one-liners for privesc, exfil, persistence, and cleanup           |

---

## 🔍 Features

Each cheat sheet is written in pure CLI (PowerShell or Bash), and includes:

### 📌 System Enumeration
- Hostname, OS version, architecture
- Hardware info, uptime, users, and groups

### 🔐 Privilege Escalation
- Add admin users
- `whoami /groups`, `sudo -l`, SUID/GUID checks
- Registry/service and cron inspection

### 🌐 Network Recon
- Interfaces, DNS, routing table
- Active connections, listening ports
- Windows: `netstat`, `Get-NetAdapter`, Linux: `ss`, `ip`, `iptables`

### 🧪 Credential Discovery
- Sensitive file search (`*pass*`, `.kdbx`, `.pem`, etc.)
- Windows Registry autoruns
- `.bash_history`, `/etc/shadow`, and config dumps on Linux

### 🛠️ Persistence
- Registry autoruns, scheduled tasks (Windows)
- `.bashrc`, cron backdoors (Linux)

### 🖥️ Screenshots (Windows GUI)
- PowerShell code to capture the desktop to `.jpg` silently

### 📤 Download / Upload / Exfiltration
- `Invoke-WebRequest`, `curl`, `wget`, `scp` examples

### 🧹 Cleanup
- Windows: `wevtutil`, file deletions
- Linux: `history -c`, `/var/log` removal

---

## 📦 Usage

Just clone or download this repo:

```bash
git clone https://github.com/yourusername/ctf-postexploitation-cheatsheets.git
