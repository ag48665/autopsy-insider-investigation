# 🕵️ Digital Forensics Investigation with Autopsy

> A digital forensic investigation performed using Autopsy 4.23.1 on the public **M57 Jean** disk image from Digital Corpora.

![Autopsy](https://img.shields.io/badge/Tool-Autopsy-blue)
![Windows](https://img.shields.io/badge/OS-Windows%20XP%20SP3-green)
![DFIR](https://img.shields.io/badge/Field-Digital%20Forensics-red)

---

# Case Information

| Field | Value |
|-------|-------|
| Case ID | DFIR-001 |
| Case Name | Insider Data Theft Investigation |
| Tool | Autopsy 4.23.1 |
| Evidence | M57 Jean (Digital Corpora) |
| Investigator | Your Name |

---

# Scenario

This project documents a forensic examination of the **M57 Jean** training disk image provided by Digital Corpora.

The objective was to identify user activity, examine system artifacts, recover evidence, and document findings using Autopsy.

---

# Objectives

- Identify system information
- Examine user accounts
- Review installed software
- Analyze recent documents
- Investigate browser history
- Review downloaded files
- Analyze e-mail artifacts
- Examine USB device history
- Review deleted files
- Document forensic findings

---

# Investigation Workflow

```
Evidence Acquisition
        │
        ▼
Import Disk Image
        │
        ▼
Autopsy Ingest Modules
        │
        ▼
Artifact Analysis
        │
        ▼
Evidence Collection
        │
        ▼
Timeline & Findings
        │
        ▼
Final Report
```

---

# Screenshots

| Screenshot | Description |
|------------|-------------|
| 01-case-overview.png | Case overview |
| 02-operating-system-information.png | Operating system information |
| 03-user-accounts.png | User accounts |
| 04-installed-programs.png | Installed applications |
| 05-recent-documents.png | Recently opened documents |
| 06-web-history.png | Browser history |
| 07-web-downloads.png | Downloaded files |
| 08-web-bookmarks.png | Browser bookmarks |
| 09-email-messages.png | Email artifacts |
| 10-usb-devices.png | USB device history |
| 11-deleted-files.png | Deleted files |
| 12-interesting-items.png | Interesting artifacts |
| 13-exif-metadata.png | Image metadata |
| 14-timeline.png | Timeline analysis |

---

# Key Findings

## Operating System

- Microsoft Windows XP Service Pack 3
- x86 Architecture

---

## User Accounts

The examination identified multiple local accounts including:

- administrator
- jean
- devon
- SYSTEM
- LOCAL SERVICE
- NETWORK SERVICE

---

## Installed Applications

Examples include:

- Mozilla Firefox
- Microsoft Office
- AIM Messenger
- Adobe Flash Player
- VMware Tools

---

## Browser Activity

Artifacts recovered include:

- Browser history
- Downloads
- Cookies
- Bookmarks
- Search history

---

## USB Devices

Multiple USB devices were identified including removable flash storage devices and an Apple iPhone.

---

## Email Artifacts

Autopsy recovered email artifacts that may provide additional context regarding user activity.

---

## Deleted Files

Deleted file artifacts were identified and reviewed as part of the investigation.

---

# Skills Demonstrated

- Digital Forensics
- DFIR
- Evidence Collection
- Browser Forensics
- USB Artifact Analysis
- File System Analysis
- Timeline Analysis
- Documentation
- Report Writing

---

# Repository Structure

```
autopsy-insider-investigation/
│
├── README.md
├── docs/
├── report/
├── screenshots/
├── evidence/
└── .gitignore
```

---

# Tools

- Autopsy 4.23.1
- Windows
- Digital Corpora M57 Jean

---

# References

- https://digitalcorpora.org/
- https://www.autopsy.com/

---

# Disclaimer

This investigation was conducted using a publicly available forensic training image provided for educational purposes.

# Author

Agata Gabara
