# Jaypocalypse Now  
*A Virus Scanner Project for CSCI150 by mbonds24*

## Overview  
**Jaypocalypse Now** is a lightweight **virus and malware scanner** developed as part of the CSCI150 course project.  
The goal of the project is to demonstrate a practical application of programming fundamentals — including file I/O, pattern recognition, data structures, and basic cybersecurity principles — by building a simple tool that scans files and directories for suspicious content or signatures.

This tool helps users understand how antivirus software identifies potential threats, using keyword matching, checksum comparison, and heuristic techniques to detect possible infections in files.+

---

## Features  
- 🔍 **Directory & File Scanning** – Recursively scans files and folders for malicious patterns.  
- 🧬 **Signature Detection** – Compares file content against known malware signatures or hashes.  
- ⚙️ **Heuristic Analysis** – Identifies suspicious files based on size, structure, or entropy.  
- 🧾 **Scan Reports** – Generates a clean, human-readable report of all files scanned and potential infections.  
- ⚡ **Command Line Interface (CLI)** – Simple terminal-based control for easy usage.  
- 🛠️ **Extensible Design** – Easily add new detection algorithms or update signature databases.

---

## Technologies Used  
- **Language:** Python 3.x *(or replace with Java/C++ if different)*  
- **Libraries:**  
  - `os`, `hashlib`, `re` – for file handling, hashing, and pattern matching  
  - `argparse` – for command line argument support  
  - *(Add any others used)*  
- **Development Tools:** Visual Studio Code, Git, etc.

---

## Getting Started  

### Prerequisites  
- Python 3.8 or later  
- Git (for cloning the repository)  

### Installation  
```bash
# Clone the repository
git clone https://github.com/mbonds24/compsci150---Jaypocalypse-Now.git
cd compsci150---Jaypocalypse-Now

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt
