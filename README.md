# 🐬 FlipSec

**Flipper Zero BadUSB Security Diagnostics**

FlipSec is an open-source security diagnostic project powered by **Flipper Zero BadUSB**. It automates basic system security checks and generates reports using simple BadUSB scripts.

The project aims to provide lightweight security auditing tools for multiple operating systems without requiring additional software installations.

## 💻 Supported Operating Systems

| Operating System | Status |
|---|---|
| 🍎 macOS | ✅ Available |
| 🪟 Windows | 🚧 Coming Soon |
| 🐧 Linux | 🚧 Coming Soon |

## 🔍 Features

The current macOS script provides:

- Operating system information
- Current user information
- Running processes
- Listening TCP ports
- Active network connections
- FileVault encryption status
- macOS firewall status
- Gatekeeper status
- Automatically generated security report

**Report filename:**

`flipsec_HH-MM-SS_DD-MM-YYYY.txt`

Reports are saved to the user's Desktop and automatically opened in TextEdit.

## 📁 Repository Structure

```text
FlipSec/
├── README.md
├── macOS.txt
├── Windows.txt  (planned)
└── Linux.txt    (planned)
```

Only `macOS.txt` is currently available.

## 🚀 Installation

1. Download `macOS.txt` from this repository.
2. Connect your Flipper Zero using a USB cable.
3. Open **qFlipper**.
4. Navigate to `SD Card/badusb/`.
5. Upload `macOS.txt`.
6. On your Flipper Zero, open **Bad USB**.
7. Select `macOS.txt`.
8. Connect to your unlocked Mac and press **Run**.

FlipSec will launch Terminal through Spotlight, perform its checks, and generate a report on your Desktop.

## 🔒 Security & Privacy

- No password extraction
- No automatic data uploads
- No administrator privileges required
- No intentional modification of system security settings
- Reports are generated and stored locally

Reports may contain sensitive information such as usernames, running processes, and network addresses. Do not publish unredacted reports.

## ⚠️ Disclaimer

FlipSec is intended for **educational purposes, personal system auditing, and authorized security testing**.

It is not an antivirus, malware removal tool, or comprehensive vulnerability scanner.

Use FlipSec only on computers you own or have explicit permission to test.

## 🛠️ Roadmap

- [x] macOS security diagnostics
- [ ] Windows security diagnostics
- [ ] Linux security diagnostics
- [ ] Automated security warnings
- [ ] Improved reporting

## 📜 License

No license has been selected yet. A license file may be added in a future release.

---

**FlipSec — Plug. Scan. Inspect
