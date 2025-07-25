# OpenPAUX: A Modern Interface for IBM Planning Analytics (TM1)

**OpenPAUX** is an open-source, cross-platform interface for IBM Planning Analytics (TM1), designed to simplify and modernize how business users interact with TM1 data.

✅ Works with:
- ✅ Excel (Windows, Mac, Web)
- ✅ Google Sheets
- ✅ Native Desktop App (Electron)

No more clunky Planning Analytics Workspace. Just fast, intuitive access to your cubes.

---

## 🔥 Why This Project?

IBM’s default TM1 interface — Planning Analytics Workspace (PAW) — is:
- Browser-only
- Bloated
- Cumbersome 
- Sluggish
- Inconsistent across platforms

This project offers:
- 🧩 Native Excel and Google Sheets add-ins
- 🖥️ A clean, responsive desktop app (Electron)
- ⚡ Direct interaction with the TM1 REST API
- 🔄 Write-back, drill-down, and cube browsing — without leaving your spreadsheet
- Cube, Dimension, TI Process, and Rule Editing

---

## 🧱 Architecture Overview

[Excel] [Google Sheets] [Electron Desktop]
\ | /
------------ [TM1 REST API] ------------
(via secure auth)

Optionally, all clients can also connect through a backend proxy for added security and data shaping.

---

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/openpaux.git
cd openpaux

| Client               | Folder                 | Docs                                           |
| -------------------- | ---------------------- | ---------------------------------------------- |
| Excel Add-in         | `excel-addin/`         | [Excel README](excel-addin/README.md)          |
| Google Sheets Add-on | `google-sheets-addon/` | [Sheets README](google-sheets-addon/README.md) |
| Electron Desktop App | `electron-client/`     | [Electron README](electron-client/README.md)   |

🔧 Configuration

Create a .env or config.json with your TM1 credentials and server info:
{
  "serverUrl": "https://your-tm1-server/api/v1",
  "authType": "Basic",
  "username": "admin",
  "password": "apple"
}

(More secure methods like OAuth or IBM CAM are supported in the backend proxy)

🛣️ Roadmap

 Read-only cube browsing

 Cross-platform Excel + Sheets support

 Writeback support

 Sandbox + workflow support

 Secure middleware proxy

 Dashboard/visualization tools


🤝 Contributing
We welcome contributions from the TM1 community! To get started:

Fork this repo

Create a feature branch

Submit a pull request with clear description

See CONTRIBUTING.md for coding guidelines.


.

📝 License
This project is licensed under the Apache 2.0 License — see the LICENSE file for details.

📫 Contact & Community
Questions? Ideas? Bugs?

Submit a GitHub Issue

Join the conversation on Reddit or [LinkedIn]

Contact the maintainer: [kielmc8@gmail.com]


