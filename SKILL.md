---
> Source: Specific Tasks & Contributions in Development Team Meetings  
> Version: 1.0 Code Name Royal Champion | Date: 2026-09-07  
> Scope: Native Desktop Application (C# WPF, Qt, Swift, Win32, JavaFX)

---

## A. Technical & Development Roles

### Software Architect

- Desktop application architecture design & technology selection (WPF, Qt, Swift, Win32, JavaFX)
- Cross-platform compatibility analysis & native framework evaluation
- System security design & OS-level defense mechanisms
- Programming language & native framework selection
- Offline-first architecture & local data persistence strategy
- OS integration pattern design (services, daemons, system tray)

### Lead Developer (Tech Lead)

- Translating business requirements into native desktop technical specifications
- Breaking down large features into measurable desktop-specific technical tasks
- Technical planning & team task allocation across OS platforms
- Bridging communication between business and native desktop technical stakeholders
- Desktop build pipeline & native dependency management oversight
- Code review standards for native UI and OS-level integration

### Desktop Application Developer

- Native user interface development (XAML, QML, Storyboard, WinForms, Swing/JavaFX)
- Accurately implementing UI designs into native desktop code
n- Integrating native UI with application logic and OS-level APIs
- Intensive collaboration with the design team on desktop UX patterns
- Cross-platform UI guideline compliance (Windows, macOS, Linux)
- Hardware API integration (file system, printer, serial port, camera, microphone)
- System tray, menu bar, native notifications & window management
- Desktop-specific UX: keyboard shortcuts, drag-and-drop, right-click context menus

### System & Integration Developer

- Desktop application logic programming & business rule implementation
- Local database management & processing (SQLite, Realm, local NoSQL, embedded DB)
- Data security & local API integration (REST/GraphQL client for sync)
- Ensuring smooth data flow between local storage and remote server
- OS-level service integration (Windows Services, LaunchAgents, systemd)
- Offline-first architecture & background sync logic
- Desktop security model implementation (sandbox, UAC, keychain, credential vault)
- Inter-process communication (IPC) & plugin/extension architecture

---

## B. Project Management & Methodology

### Project Manager (PM)

- Project schedule & budget management
- Progress & work alignment monitoring across OS platform teams
- Managing team workload to prevent burnout
- Identifying & handling delay risks
- Coordinating multi-OS release timelines & platform-specific milestones

### Scrum Master

- Implementing & facilitating Agile/Scrum methodologies
- Managing work cycles (Sprints)
- Facilitating daily standup meetings
- Identifying bottlenecks & ensuring smooth team workflow
- Managing cross-platform development dependencies & blockers

---

## C. Design & User Research

### UX Designer

- Designing desktop application flows & functionality
- Researching user behavior & needs for desktop power users
- Creating user journey maps for offline/online hybrid scenarios
- Designing wireframes for native desktop patterns (multi-window, docking, panels)
- Keyboard shortcut & accessibility design for desktop environments

### UI Designer

- Visual design & aesthetics creation for native desktop platforms
- Selecting colors, typography, icons, & buttons aligned with OS design language
- Designing interface layouts for resizable windows & multi-monitor support
- Aligning visual style with product identity & native OS Human Interface Guidelines
- Dark mode, high-DPI, and accessibility contrast compliance

### UX Researcher

- Conducting usability testing on target desktop OS environments
- Gathering & analyzing feedback from real users on native desktop workflows
- Formulating recommendations for improvement on desktop-specific pain points
- Directly validating designs with target users across Windows, macOS, and Linux
- Testing offline usage scenarios & recovery workflows

---

## D. Testing & Security

### QA Engineer (Manual)

- Functional testing from the perspective of real desktop users
- Designing test cases for native desktop interactions
- Reporting product defects & workflow discrepancies
- Testing negative scenarios & system limits
- Cross-OS compatibility testing (Windows, macOS, Linux distributions)
- Installer & uninstaller validation across OS versions
- Offline mode functionality testing & network recovery scenarios
- OS permission, UAC, and gatekeeper/security prompt testing
- High-DPI display, multi-monitor, and resolution change testing
- Keyboard navigation & screen reader accessibility testing

### QA Automation Engineer

- Writing automated test scripts for desktop UI (Selenium, WinAppDriver, Appium, Squish)
- Integrating testing tools into the CI/CD Pipeline
- Continuous testing with every code update
- Automating key feature verification to save time
- Automated installer smoke testing & regression suites
- Cross-platform automated build verification

### Security Tester (Penetration Tester)

- Identifying system security vulnerabilities in desktop applications
- Testing resilience against cyber attacks on local data & network sync
- Analyzing risks of data leaks, malicious code injection & local privilege escalation
- Formulating security recommendations prior to application release
- OS-level security audit (registry, plist, keychain, credential store)
- Reverse engineering resistance & code obfuscation validation

---

## E. Infrastructure & Deployment

### DevOps Engineer

- Setting up automated build pipelines (CI/CD Pipeline) for multi-OS desktop builds
- Automating application testing & deployment across Windows, macOS, and Linux
- Integrating development–deployment workflows for native binaries
- Deploying updates automatically, quickly, & securely via auto-updater
- Managing cross-compilation environments & native dependency caching

### System Administrator (SysAdmin)

- Build server health management & monitoring (Windows, macOS, Linux agents)
- Cloud infrastructure management for update servers & telemetry
- Storage capacity & workload monitoring for build artifacts
- Preventing service downtime during high traffic on update delivery
- Code signing server & certificate infrastructure management

### Release Manager

- Application release schedule planning across multiple desktop OS platforms
- Verifying legal & technical compliance per OS vendor requirements
- Controlling release readiness & staged rollout (canary releases)
- Publishing to official app stores (Microsoft Store, Mac App Store, Snap/Flatpak)
- Building OS-specific installers (.msi, .dmg, .AppImage, .deb, .rpm)
- Code signing certificate management & renewal (EV Code Signing, Apple Developer ID)
- Auto-updater integration & delta update pipeline (Squirrel, Sparkle, electron-updater analog)
- Release note generation & in-app update notification management
- End-of-life (EOL) & deprecation policy enforcement

---

## F. Strategy & Business Requirements

### Product Manager (PM)

- Aligning business vision with native desktop technical execution
- Drafting long-term product roadmaps for desktop platform expansion
- Market competition & competitor analysis for desktop software segment
- Defining product goals & success metrics (DAU, retention, crash rate, update adoption)

### Product Owner (PO)

- Managing the prioritized work list (Backlog)
- Breaking down requirements into user stories for desktop-native features
- Work cycle planning & task detailing with OS platform constraints in mind
- Prioritizing work based on highest business value & platform parity

---

> **Note:** This directory is tailored for native desktop application projects. For web-based or hybrid (Electron/Tauri) desktop applications, refer to the standard web-oriented skill directory.
