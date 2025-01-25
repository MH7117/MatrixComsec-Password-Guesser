# 🔒 MatrixComsec Password Guesser v3.0

**Advanced Ethical Security Testing Tool**

![Script Screenshot](https://raw.githubusercontent.com/MH7117/MatrixComsec-Password-Guesser/refs/heads/main/MatrixComsec-Password-Guesser-Screen-Shot.png)

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-green.svg)](https://www.python.org/)
```markdown

---

## 🌟 Key Features

- **Dual Attack Modes**
  - 🕸️ **Browser Automation**: Uses Selenium for precise testing.
  - ⚡ **Direct Server Requests**: Leverages the Requests library for faster testing.
- **Proxy Rotation & IP Cycling**: Bypass rate limits and improve anonymity.
- **Advanced Error Detection**: Handles unauthorized responses (403, 401, etc.).
- **Logging System**: Success and failure results saved to `success.txt`.
- **User Role Mapping**: Manage and assign roles efficiently.

---

## 📁 Required Files

Before running the script, ensure you have the following files in the same directory:

1. `ips.txt`: List of target IP addresses (one per line)
2. `proxies.txt`: List of proxy servers (optional, one per line in IP:PORT format)
3. `chromedriver.exe`: ChromeDriver executable (matching your Chrome browser version)

The script will create `success.txt` automatically to store successful results. If it doesn't exist, you can create it manually.

---

## 🛠️ Installation Guide

### Prerequisites

- **Python**: Version 3.9+
- **Chrome Browser**: Ensure matching Chromedriver version.

### Steps

```bash
# Install dependencies
pip install selenium requests colorama

# Download Chromedriver
# Visit: https://chromedriver.chromium.org/
# Place chromedriver.exe in the project folder
```

## 🚀 Getting Started

### Prepare Input Files

1. **`ips.txt`**: List of target IPs (one IP per line).
2. **`list.txt`**: Passwords to test (one password per line).
3. **`proxies.txt`** (Optional): Proxies in `ip:port` format.

### Run the Tool

```bash
python MatrixComsec-Password-Guesser.exe
```

### Follow Interactive Prompts

1. **Choose Mode**: Browser or Direct Requests.
2. **Select User**: Input or choose predefined user roles.
3. **Proxy Settings**: Enable/disable proxy usage.
4. **Threads**: Specify the number of threads for concurrent execution.

---

## 📂 Input File Examples

### `ips.txt`

```plaintext
192.168.1.1
10.0.0.2
```

### `proxies.txt`

```plaintext
203.0.113.1:8080
198.51.100.2:3128
```

### `list.txt` (Passwords)

```plaintext
admin
P@ssw0rd
2025
```

## 📊 Output

Successful results will be saved in `success.txt`. The script will create this file if it doesn't exist.

---

## 📚 Documentation

- [Changelog](https://github.com/MH7117/MatrixComsec-Password-Guesser/blob/main/CHANGELOG.md)
- [Contribution Guidelines](https://github.com/MH7117/MatrixComsec-Password-Guesser/blob/main/Contribution%20Guidelines.txt)
- [Legal Disclaimer](https://github.com/MH7117/MatrixComsec-Password-Guesser/blob/main/Legal%20Disclaimer.txt)
- [License Agreement](https://github.com/MH7117/MatrixComsec-Password-Guesser/blob/main/License%20Agreement.txt)
- [Terms of Use](https://github.com/MH7117/MatrixComsec-Password-Guesser/blob/main/Terms%20of%20Use.txt)

---

## 🤝 Contributing

We welcome contributions to improve this tool! Please follow our [Contribution Guidelines](https://github.com/MH7117/MatrixComsec-Password-Guesser/blob/main/Contribution%20Guidelines.txt).

---

## 📧 Contact & Support

- **GitHub**: [H7117](https://github.com/MH7117)
- **Official Website**: SMS & ShortCall Tools
- **Report Issues**: Use the [GitHub Issues](https://github.com/MH7117/MatrixComsec-Password-Guesser/issues) section.

---

## ⚠️ Legal Notice

This tool is strictly for authorized security testing. By using this software, you agree to the following:
- [Terms of Use](https://github.com/MH7117/MatrixComsec-Password-Guesser/blob/main/Terms%20of%20Use.txt)
- [Legal Disclaimer](https://github.com/MH7117/MatrixComsec-Password-Guesser/blob/main/Legal%20Disclaimer.txt)

---

**Copyright © 2025 H7117. Licensed under [GNU GPLv3](https://www.gnu.org/licenses/gpl-3.0).**
```
