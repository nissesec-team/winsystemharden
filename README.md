# WinSystemHarden (Free)

Free Windows hardening tool with one-click rollback. Windows 10 / 11.

WinSystemHarden applies 33 hardening rules inspired by CIS Benchmarks and NSA guidelines. It blocks inbound traffic on high-risk ports, disables SMBv1 and other legacy protocols, and locks down services, accounts and permissions. If anything breaks, roll it back by batch.

## ✨ Key Features

- **33 hardening rules** across Network, Service, System, Account and Permission.
- **Three plans**: Standard (24 rules), Deep (all 33), Custom (pick your own).
- **One-click hardening**: apply every selected rule in a single run.
- **Rollback by batch**: revert a batch and everything applied after it.
- **Interrupted runs are recoverable**: if the app closes, crashes, or the machine reboots mid-batch, the next launch detects it and lets you resume or roll back.
- **Inspired by CIS and NSA guidance**, adapted for real-world compatibility.
- **No account, no telemetry.** The only network call is the manual Check Update button, which fetches a version string.
- **Free, no license key.**

Nine of the 33 rules are Deep-plan only and are marked in orange in the UI. They carry compatibility risk, so read the label before enabling them.

## 📥 Download

Get the latest build from the [Releases](https://github.com/nissesec-team/winsystemharden/releases/latest) page.

The installer is a standard Windows wizard. There is no silent install, so you can see exactly what gets changed before it runs.

Requirements: Windows 10 or 11. .NET Framework 4.8 ships with both, nothing else to install.

## 📘 User Guide

The PDF is included in the installer and also attached to each release on the [Releases](https://github.com/nissesec-team/winsystemharden/releases/latest) page.

## 🔐 Security

Every release lists its SHA-256 and a VirusTotal report on the [release page](https://github.com/nissesec-team/winsystemharden/releases/latest). If the hash you compute doesn't match the value shown there, don't run the file.

## ⚖️ License & Source

Proprietary, free to use. The source code is not public.

The files GitHub shows under "Source code" in Releases are default repository snapshots containing only this README. The application itself is distributed as an executable.

© 2026 Nisse-Sec Team. All rights reserved.
