# HTB Write-ups

A collection of detailed walkthroughs, documentation, and methodology notes for **Hack The Box** machines.

## Purpose

This repository serves as a personal knowledge base where I document the full process of solving HTB machines — from initial reconnaissance and enumeration through privilege escalation and root/owner flags. Each write-up aims to be thorough, reproducible, and educational.

## Structure

```
.
├── machines/
│   ├── <machine-name>/
│   │   ├── README.md        # Full walkthrough
│   │   ├── screenshots/     # Supporting images
│   │   └── files/           # Scripts, exploits, or configs used
│   └── ...
├── documentation/           # General notes, techniques, and cheat sheets
└── README.md                # This file
```

## Write-up Format

Each machine write-up follows a consistent structure:

1. **Machine Info** — Name, OS, difficulty, IP address
2. **Reconnaissance** — Nmap scans, service discovery, initial enumeration
3. **Foothold** — Vulnerability identification, exploitation
4. **Privilege Escalation** — Post-exploitation, lateral movement, root
5. **Flags** — User and root flags
6. **Key Takeaways** — Lessons learned, interesting techniques, commands worth remembering

## Contents

| Machine  | OS      | Difficulty | Write-up        |
| -------- | ------- | ---------- | --------------- |
| Fawn     | Linux   | Very Easy  | [[🦌 Fawn]]     |
| Dancing  | Windows | Very Easy  | [[🩰 Dancing]]  |
| Redeemer | Linux   | Very Easy  | [[💾 Redeemer]] |

*(Table to be filled as machines are completed.)*

## Disclaimer

- These write-ups are intended for **educational purposes only**.
- All machines are from [Hack The Box](https://www.hackthebox.com/) and should only be accessed by users with an active VIP subscription.
- Do not use these techniques against systems without explicit permission.

## Tools & Resources

- **Nmap** — Network discovery and enumeration
- **Burp Suite** — Web application testing
- **Metasploit** — Exploitation framework
- **LinPEAS / WinPEAS** — Privilege escalation enumeration
- **netcat / socat** — Reverse shells and networking
- **Python / Bash** — Custom scripts and automation

## License

This project is for personal documentation. All walkthroughs are original content unless otherwise attributed.
