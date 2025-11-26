# santas-secret-workshop-ctf
Santa’s Secret Workshop CTF – holiday-themed cybersecurity challenge pack (PCAP, binaries, web app, config, write-up)

# Santa’s Secret Workshop CTF

This repository contains all the challenge files for the **Santa’s Secret Workshop** CTF.  
Participants can clone or download this repo to access the challenges, solve them locally, and extract flags.

## Overview

- Theme: North-Pole / Santa’s Workshop — elf emails, encrypted wish lists, a reindeer portal, toy-factory configs, and a magic key binary.  
- Contents: Each challenge lives in its own folder under `challenges/`.  
- Purpose: Offline / download-based challenges — participants run tools or local servers, then extract and submit flags.  
- After the CTF: Optional solutions or hints can be stored in `writeups/` (if you choose to include them).

## How to Use

```bash
git clone https://github.com/<your-username>/santas-secret-workshop-ctf.git
cd santas-secret-workshop-ctf
```

Then go into the `challenges/` directory and select the challenge you want to work on. Each folder contains the necessary files (pcap, binaries, zipped web apps, etc.).

Once you solve a challenge and find a flag, submit it to your CTF platform (e.g., TryHackMe, CTFd, etc.).

## Folder Structure

| Path | Description |
|------|-------------|
| `challenges/elf_email_log/elf_mailbox.pcap` | PCAP file capturing elf email traffic — for network forensics (SMTP) challenge. |
| `challenges/wish_list_cipher/` | Encrypted wish list and decryption key — crypto challenge. |
| `challenges/reindeer_web_portal/` | Zipped vulnerable web application — web exploitation challenge. |
| `challenges/toy_factory_config/` | Zipped toy-factory config server — path-traversal / config disclosure challenge. |
| `challenges/magic_key_binary/` | Compiled binary for reverse-engineering / passphrase challenge. |
| `writeups/` (optional) | Post-CTF walkthroughs or hints — include only after the event if you want to reveal solutions. |

## What You’ll Learn

- Forensics: analyzing packet captures, reconstructing TCP streams, decoding base64.  
- Cryptography: symmetric encryption and decryption (Fernet / Python).  
- Web exploitation: login bypass, injection, configuration mis-use.  
- Misconfiguration & file disclosure: directory traversal and config file exposure.  
- Reverse engineering: analyzing binaries, extracting secrets, and executing them.

## Notes & Recommendations

- This repo is meant for **challenge distribution only** — do not include flags or full solutions in the challenge folders unless after the event.  
- Use a `.gitignore` if you want to avoid tracking unnecessary files (e.g. OS-specific metadata, personal editor settings).  
- Encourage participants to solve locally and avoid sharing flags publicly until after the CTF is done.  
- The repository uses Markdown for documentation so it’s easily readable on GitHub.  

Enjoy 🛠️ and happy hacking!  
