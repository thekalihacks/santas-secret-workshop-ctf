# Setup Guide for Santa’s Secret Workshop CTF

Use this guide to prepare your environment before attempting the challenges. It supports both **macOS** and **Windows**.  

---

## macOS & Windows — Setup Instructions


#macOS setup instructions:

# 1. (Optional) Install Homebrew if not installed yet
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

# 2. Update Homebrew and install Python 3
```bash
brew update
brew install python
```

# 3. Verify installation
```bash
python3 --version
pip3 --version
```

# 4. (Recommended) Create and activate a Python virtual environment
```bash
python3 -m venv ctf-env
source ctf-env/bin/activate
```

# 5. Install required Python packages
```bash
pip install cryptography
pip install scapy
```

If pip3 install … fails (for example due to missing components or pip), you can use:
```bash
python3 -m ensurepip --upgrade
```

# Windows — Setup Instructions
Download the latest Python 3 installer from python.org — choose the Windows installer. During installation, make sure to check “Add Python 3 to PATH”. 

After installation, open a new Command Prompt or PowerShell window, and verify:

python --version
pip --version

(Recommended) Create and activate a virtual environment:

python -m venv ctf-env
ctf-env\Scripts\activate

Install required Python packages:

pip install cryptography
pip install scapy

If pip is missing or not functioning, you can initialise it with:
python -m ensurepip --upgrade

Additional Tools (Recommended, Not Always Required)
A packet analysis tool (e.g. Wireshark or TShark) — for tasks involving PCAP / network forensic analysis.
A code editor or terminal of your choice (e.g. Visual Studio Code, default shell, PowerShell, macOS Terminal, etc.).
Internet connection (for installing packages).
