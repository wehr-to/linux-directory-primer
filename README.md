# 🐧 linux-directory-primer

This repository documents the **50 most essential Linux directories** for infrastructure, security, automation, and forensic engineering. Whether you're securing the OS, responding to an incident, or writing cloud-init, this repo gives you the internal map.

## 📦 Why This Repo Exists

You can’t secure or automate Linux if you don’t understand what lives where.

This repo is a **ground-level guide to the Linux filesystem**, grouped by purpose and written for operators, defenders, and builders.

## 📁 Grouped Coverage

| Group | Focus |
|-------|-------|
| `core-system/` | Binary locations, boot logic, and shared libs |
| `runtime-and-virtual/` | In-memory systems that expose kernel and hardware info |
| `configuration/` | All things `/etc/` — passwords, network, systemd, cron |
| `user-space/` | Where user data lives (`/home`, `/tmp`, `/var`) |
| `system-management/` | Init, systemd, udev, logging |
| `security/` | Audit, AppArmor, SELinux, shadow, SUID issues |
| `packaging/` | Snap, Flatpak, local binaries, `/opt` vs `/usr/local` |
| `forensics-and-triage/` | Logs, deleted files, open FDs, file system abuse |
| `reference/` | FHS overview, diagrams, logging maps |

## 🧠 Examples of What You'll Learn

- How `/proc` reveals running processes, files, and memory
- What `/dev/shm` and `/tmp` mean for attackers and defenders
- Why `/usr`, `/bin`, and `/opt` have distinct use cases
- Where auditd, journald, and syslog write to and how to trace them
- What logs live in `/var` and how to pivot to them quickly

## 🔐 Ideal For:

- Cloud and automation engineers
- Blue teamers and incident responders
- DevOps engineers doing secure provisioning
- Students prepping for Linux+, RHCSA, or OSCP
