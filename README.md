# IT Project — Codename: RoyalChampion

> **Skill Directory for Native Desktop Application Development**

---

## About This Repository

This repository contains a **Skill Directory** specifically designed for **Native Desktop** application development teams (not web or hybrid). This directory maps the roles, responsibilities, and skill sets required to build high-quality desktop applications running natively on Windows, macOS, and Linux.

> **Difference from other repos:** This repository is the **Native Desktop** version of the skill directory. If you are looking for a skill directory for web/SaaS-based projects, please visit our sister repository: [`it-project-codename-grandwarden`](https://github.com/ifredrix/it-project-codename-grandwarden).

---

## Project Scope

This skill directory covers the entire **Software Development Life Cycle (SDLC)** for native desktop applications:

| Phase | Related Roles |
| --- | --- |
| **Strategy & Business** | Product Manager, Product Owner |
| **Design & Research** | UX Designer, UI Designer, UX Researcher |
| **Development** | Software Architect, Lead Developer, Desktop Application Developer, System & Integration Developer |
| **Testing & Security** | QA Engineer (Manual), QA Automation Engineer, Security Tester |
| **Deployment & Infrastructure** | DevOps Engineer, System Administrator, Release Manager |
| **Project Management** | Project Manager, Scrum Master |

---

## File Structure

```javascript
it-project-codename-royalchampion/
├── SKILL.md          ← Complete Skill Directory (17 roles, 6 categories)
├── README.md         ← This document
└── (future assets)

```

### SKILL.md

The main file containing detailed descriptions for each role within the team, including:

* **6 Categories** of roles (Technical, PM, Design, Testing, Infrastructure, Strategy)
* **17 Specific** roles
* Skills & tasks tailored for the **native desktop** context (WPF, Qt, Swift, Win32, JavaFX)

---

## Supported Technologies & Platforms

This skill directory is designed for teams using native desktop technologies such as:

| Platform | Framework / Technology |
| --- | --- |
| **Windows** | WPF, WinForms, WinUI 3, UWP |
| **macOS** | Swift, SwiftUI, AppKit, Cocoa |
| **Linux** | Qt, GTK, JavaFX |
| **Cross-Platform** | Qt (C++), Avalonia UI, Uno Platform |

---

## Team Workflow Based on Skill Directory

```javascript
Product Manager & Product Owner
        ↓
UX Designer → UI Designer → UX Researcher
        ↓
Software Architect + Lead Developer
        ↓
Desktop Application Developer + System & Integration Developer
        ↓
QA Manual + QA Automation + Security Tester
        ↓
DevOps + SysAdmin + Release Manager
        ↓
Release to Microsoft Store / Mac App Store / Linux Repositories

```

> **Project Manager** and **Scrum Master** oversee and coordinate the entire workflow above.

---

## When to Use This Directory?

Use this skill directory if your project meets the following criteria:

* [x] The application runs **natively** on desktop (not in a browser)
* [x] Requires access to **hardware** or **OS-level APIs** (file system, printer, serial port, etc.)
* [x] Requires an **offline-first** architecture with background synchronization
* [x] Needs to be distributed via **installers** (.msi, .dmg, .AppImage) or app stores
* [x] Requires an **auto-updater** and **code signing**
* [x] Requires **multi-OS** support (Windows, macOS, Linux)

---

## When NOT to Use This Directory?

Do not use this directory if your project is:

* [ ] **Web-based** or **SaaS** applications → use [`grandwarden`](https://github.com/ifredrix/it-project-codename-grandwarden)
* [ ] **Native mobile** applications (iOS/Android)
* [ ] **Hybrid desktop** applications based on Electron / Tauri → can still be used with minor tweaks, but not optimal
* [ ] **AI/ML**, **game**, **IoT**, or **blockchain** projects

---

## How to Use

1. **Read `SKILL.md**` to understand all available roles and skills.
2. **Adjust according to your team size:**

* **Small team (5–7 people):** Several roles can be combined (e.g., PM + Scrum Master, UX + UI, DevOps + SysAdmin).
* **Large team (15–25 people):** Each role can be assigned to a dedicated person, or even multiple people per role.

3. **Add specialist roles** if needed (e.g., C++ Specialist for Qt, Windows Driver Developer, etc.).
4. **Use as a reference** for:

* Writing job descriptions
* Team performance evaluation
* Identifying skill gaps within the team
* Hiring planning

---

## Contributing

If you find roles or skills that are less relevant to native desktop development, or wish to add new technologies, feel free to open an **issue** or submit a **pull request**.

---

> *"Built for the desktop. Engineered for the native experience."*
