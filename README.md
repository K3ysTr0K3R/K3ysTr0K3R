<div align="center">

# Jared Brits

### `K3ysTr0K3R`

**Cybersecurity Researcher · Ethical Hacker · Exploit Developer**

[![GitHub](https://img.shields.io/badge/GitHub-K3ysTr0K3R-181717?style=for-the-badge\&logo=github)](https://github.com/K3ysTr0K3R)
[![Exploit Database](https://img.shields.io/badge/Exploit--DB-Research-8B0000?style=for-the-badge)](https://www.exploit-db.com/)
[![Open Source](https://img.shields.io/badge/Open--Source-Research-2ea44f?style=for-the-badge\&logo=github)](https://github.com/K3ysTr0K3R)

<br>

> **Research. Break. Understand. Build. Document.**

</div>

---

# About Me

I'm **Jared Brits**, better known online as **K3ysTr0K3R**.

I'm a cybersecurity researcher and ethical hacker focused on **vulnerability research, exploit development, reconnaissance, security automation, and building security tools**.

My work revolves around understanding how vulnerable software and exposed infrastructure behave, turning that research into reproducible proof-of-concepts, and building tools that make security testing faster and more practical.

My primary areas of interest include:

* Vulnerability research
* Exploit development
* Proof-of-concept development
* Web application security
* Network security
* IoT and embedded-device security
* Reconnaissance and fingerprinting
* Vulnerability scanning
* Security automation
* Open-source security tooling

I use GitHub as a public research notebook and development environment where I publish tools, experiments, proof-of-concepts, and security research.

---

# Research Focus

```text
                 K3ysTr0K3R
                      │
       ┌──────────────┼──────────────┐
       │              │              │
       ▼              ▼              ▼
 Vulnerability    Reconnaissance   Exploit
   Research         & Scanning    Development
       │              │              │
       └──────────────┼──────────────┘
                      │
                      ▼
               Security Tooling
                      │
                      ▼
             Reproducible PoCs
                      │
                      ▼
             Open-Source Research
```

---

# Featured Security Projects

## cPanelScanner

**Fast, multi-threaded cPanel discovery tool written in Go.**

cPanelScanner is designed to identify exposed cPanel / WHM services across IP ranges, CIDR blocks, and target lists.

**Highlights**

* Written in Go
* Concurrent scanning
* CIDR support
* Target-list support
* cPanel service detection
* Ports `2082`, `2083`, and `2087`

**Repository:**
https://github.com/K3ysTr0K3R/cPanelScanner

---

## CamTRON

**Camera and surveillance-device detection scanner written in Go.**

CamTRON focuses on identifying network-accessible cameras, DVRs and NVRs through device fingerprinting.

**Highlights**

* Go-based concurrent scanner
* Camera/device fingerprinting
* Support for numerous vendors
* CIDR and range scanning
* CSV output
* Network reconnaissance

**Repository:**
https://github.com/K3ysTr0K3R/CamTRON

---

## INtrack

**Internet crawler and security scanner written in Python.**

INtrack is designed for large-scale reconnaissance and technology discovery, combining host discovery, service detection, technology identification and vulnerability-oriented enumeration.

**Highlights**

* Python
* Multi-threaded scanning
* Host and subnet scanning
* Technology detection
* Web-service enumeration
* IoT discovery
* CVE-oriented detection
* Internet-scale reconnaissance capabilities

**Repository:**
https://github.com/K3ysTr0K3R/INtrack

---

## Routeglass

**High-speed router and network-appliance fingerprinting tool written in Go.**

Routeglass identifies exposed routers, firewalls and embedded network devices by analyzing HTTP responses against device fingerprints.

**Highlights**

* Written in Go
* High-speed concurrent scanning
* Router fingerprinting
* Firewall/device identification
* IPv4 range support
* CIDR support
* Custom user-agent support

**Repository:**
https://github.com/K3ysTr0K3R/Routeglass

---

## MikroTik Winbox Scanner

**Winbox protocol scanner for MikroTik RouterOS.**

A concurrent scanner designed to identify exposed MikroTik Winbox services and assist with security research surrounding RouterOS infrastructure.

**Highlights**

* Go
* Concurrent scanning
* Winbox service discovery
* TCP `8291` detection
* RouterOS reconnaissance
* CVE-2018-14847 research support

**Repository:**
https://github.com/K3ysTr0K3R/MikroTik-Winbox-Scanner

---

## Ingram

**Webcam and DVR vulnerability scanning tool.**

Ingram focuses on identifying vulnerable internet-connected camera and DVR infrastructure from supported vendors.

**Research areas include:**

* IP cameras
* DVRs
* Network video devices
* Hikvision
* Dahua
* Vulnerability discovery

**Repository:**
https://github.com/K3ysTr0K3R/Ingram

---

# Security Tooling

My repositories cover several categories of offensive-security research tooling.

### Reconnaissance

* Internet-scale discovery
* Host enumeration
* Service detection
* Technology fingerprinting
* Router fingerprinting
* Camera/DVR discovery
* Network appliance identification

### Vulnerability Scanning

* Web vulnerabilities
* Remote code execution
* Authentication vulnerabilities
* Network appliance vulnerabilities
* IoT vulnerabilities
* Known-CVE detection

### Exploit Development

* Remote Code Execution
* Command Injection
* Authentication Bypass
* Arbitrary File Read
* Privilege Escalation
* Web application vulnerabilities
* Network appliance vulnerabilities

### Security Automation

* Concurrent scanning
* Automated enumeration
* Target-list processing
* CIDR processing
* Output generation
* GitHub Actions automation

---

# Languages

<p align="center">

<img src="https://skillicons.dev/icons?i=python,go,bash,ruby" />

</p>

| Language   | Primary Use                                                           |
| ---------- | --------------------------------------------------------------------- |
| **Python** | Security research, PoCs, automation, scanners and reconnaissance      |
| **Go**     | High-performance scanners, concurrent networking and security tooling |
| **Bash**   | Linux automation, scripting and security workflows                    |
| **Ruby**   | Security tooling, scripting and exploit-development environments      |

---

# Technologies

<p align="center">

<img src="https://skillicons.dev/icons?i=linux,docker,git,github,vim" />

</p>

```text
Linux
Git / GitHub
GitHub Actions
Docker
Vim
CLI Security Tooling
Network Reconnaissance
Concurrent Scanning
Vulnerability Research
Exploit Development
```

---

# GitHub Automation & Workflows

I use **GitHub Actions** to automate parts of my GitHub environment and development workflow.

## Contribution Snake

One of my repository workflows generates the animated GitHub contribution snake.

```text
.github/
└── workflows/
    └── snake.yml
```

The workflow automates generation of the contribution visualization used throughout my profile.

<p align="center">

<img src="https://raw.githubusercontent.com/K3ysTr0K3R/K3ysTr0K3R/output/github-contribution-grid-snake.svg" alt="GitHub Contribution Snake">

</p>

### Automation Stack

```text
GitHub Actions
      │
      ├── Automated workflows
      ├── Scheduled execution
      ├── Repository automation
      ├── Contribution visualization
      └── GitHub profile tooling
```

---

# Exploit Development

A significant part of my work involves researching publicly disclosed vulnerabilities and developing reproducible proof-of-concept implementations.

My exploit repositories span multiple generations of vulnerabilities, including:

* Remote Code Execution
* Authentication Bypass
* Command Injection
* Arbitrary File Read
* Privilege Escalation
* Web Application vulnerabilities
* Network appliance vulnerabilities
* IoT vulnerabilities

---

# CVE Exploit Portfolio

<details>
<summary><b>2024</b></summary>

* [CVE-2024-10914](https://github.com/K3ysTr0K3R/CVE-2024-10914-EXPLOIT)
* [CVE-2024-27198](https://github.com/K3ysTr0K3R/CVE-2024-27198-EXPLOIT)
* [CVE-2024-25600](https://github.com/K3ysTr0K3R/CVE-2024-25600-EXPLOIT)
* [CVE-2024-4577](https://github.com/K3ysTr0K3R/CVE-2024-4577-EXPLOIT)
* [CVE-2024-3273](https://github.com/K3ysTr0K3R/CVE-2024-3273-EXPLOIT)

</details>

<details>
<summary><b>2023</b></summary>

* [CVE-2023-51467](https://github.com/K3ysTr0K3R/CVE-2023-51467-EXPLOIT)
* [CVE-2023-23752](https://github.com/K3ysTr0K3R/CVE-2023-23752-EXPLOIT)
* [CVE-2023-32315](https://github.com/K3ysTr0K3R/CVE-2023-32315-EXPLOIT)
* [CVE-2023-43208](https://github.com/K3ysTr0K3R/CVE-2023-43208-EXPLOIT)

</details>

<details>
<summary><b>2022</b></summary>

* [CVE-2022-33891](https://github.com/K3ysTr0K3R/CVE-2022-33891-EXPLOIT)
* [CVE-2022-34753](https://github.com/K3ysTr0K3R/CVE-2022-34753-EXPLOIT)
* [CVE-2022-0165](https://github.com/K3ysTr0K3R/CVE-2022-0165-EXPLOIT)

</details>

<details>
<summary><b>2021</b></summary>

* [CVE-2021-43798](https://github.com/K3ysTr0K3R/CVE-2021-43798-EXPLOIT)
* [CVE-2021-42013](https://github.com/K3ysTr0K3R/CVE-2021-42013-EXPLOIT)
* [CVE-2021-4191](https://github.com/K3ysTr0K3R/CVE-2021-4191-EXPLOIT)
* [CVE-2021-34621](https://github.com/K3ysTr0K3R/CVE-2021-34621-EXPLOIT)
* [CVE-2021-22873](https://github.com/K3ysTr0K3R/CVE-2021-22873-EXPLOIT)

</details>

<details>
<summary><b>2019</b></summary>

* [CVE-2019-15107](https://github.com/K3ysTr0K3R/CVE-2019-15107-EXPLOIT)
* [CVE-2019-17382](https://github.com/K3ysTr0K3R/CVE-2019-17382-EXPLOIT)

</details>

<details>
<summary><b>2018</b></summary>

* [CVE-2018-14847](https://github.com/K3ysTr0K3R/CVE-2018-14847-EXPLOIT)
* [CVE-2018-9995](https://github.com/K3ysTr0K3R/CVE-2018-9995-EXPLOIT)

</details>

<details>
<summary><b>2017</b></summary>

* [CVE-2017-8225](https://github.com/K3ysTr0K3R/CVE-2017-8225-EXPLOIT)
* [CVE-2017-7921](https://github.com/K3ysTr0K3R/CVE-2017-7921-EXPLOIT)
* [CVE-2017-5487](https://github.com/K3ysTr0K3R/CVE-2017-5487-EXPLOIT)

</details>

<details>
<summary><b>2015</b></summary>

* [CVE-2015-2166](https://github.com/K3ysTr0K3R/CVE-2015-2166-EXPLOIT)

</details>

<details>
<summary><b>2014</b></summary>

* [CVE-2014-6271](https://github.com/K3ysTr0K3R/CVE-2014-6271-EXPLOIT)

</details>

<details>
<summary><b>2010</b></summary>

* [CVE-2010-4231](https://github.com/K3ysTr0K3R/CVE-2010-4231-EXPLOIT)

</details>

<details>
<summary><b>2008</b></summary>

* [CVE-2008-5862](https://github.com/K3ysTr0K3R/CVE-2008-5862-EXPLOIT)

</details>

---

# Exploit-DB Research

Some of my vulnerability research has also been published/indexed through the **Exploit Database**.

### CVE-2024-25600

**WordPress Bricks Builder Theme — Remote Code Execution**

Exploit-DB: **EDB-ID 52619**

[View on Exploit-DB](https://www.exploit-db.com/exploits/52619)

---

### CVE-2026-48907

**Joomla JCE — Unauthenticated Remote Code Execution**

Exploit-DB: **EDB-ID 52630**

[View on Exploit-DB](https://www.exploit-db.com/exploits/52630)

---

### D-Link DNS-340L

**OS Command Injection**

An Exploit-DB entry associated with my research covers OS command injection affecting D-Link NAS devices.

[Explore Exploit-DB](https://www.exploit-db.com/)

---

# Research Workflow

I approach vulnerability research as a repeatable process rather than simply writing an exploit and moving on.

```text
             Target / Software
                    │
                    ▼
             Reconnaissance
                    │
                    ▼
              Enumeration
                    │
                    ▼
          Vulnerability Analysis
                    │
                    ▼
             Root Cause Study
                    │
                    ▼
             PoC Development
                    │
                    ▼
            Reproducible Testing
                    │
                    ▼
              Documentation
                    │
                    ▼
           Responsible Disclosure
```

---

# Security Research Philosophy

```text
Understand the vulnerability.
        ↓
Understand why it exists.
        ↓
Build a reproducible demonstration.
        ↓
Validate the impact.
        ↓
Document the findings.
        ↓
Share knowledge responsibly.
```

My security tooling and proof-of-concept repositories are intended for **authorized testing, vulnerability research, defensive security validation and education**.

Only test systems you own or have explicit permission to assess.

---

# GitHub Achievements

My GitHub activity includes recognized profile achievements such as:

* **Starstruck**
* **Quickdraw**

My GitHub profile has also grown into a sizeable collection of public security research repositories covering scanners, reconnaissance tools, PoCs and experiments.

---

# GitHub Stats

<p align="center">

<img src="https://komarev.com/ghpvc/?username=K3ysTr0K3R&style=for-the-badge" alt="Profile Views">

</p>

<p align="center">

<img src="https://github-readme-stats.vercel.app/api?username=K3ysTr0K3R&show_icons=true&theme=dark&hide_border=true" alt="GitHub Stats">

</p>

<p align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=K3ysTr0K3R&layout=compact&theme=dark&hide_border=true" alt="Top Languages">

</p>

<p align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=K3ysTr0K3R&theme=black-ice&hide_border=true" alt="GitHub Streak">

</p>

---

# Featured Repositories

<p align="center">

<a href="https://github.com/K3ysTr0K3R/INtrack">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=K3ysTr0K3R&repo=INtrack&theme=dark&hide_border=true">
</a>

<a href="https://github.com/K3ysTr0K3R/Routeglass">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=K3ysTr0K3R&repo=Routeglass&theme=dark&hide_border=true">
</a>

</p>

<p align="center">

<a href="https://github.com/K3ysTr0K3R/CamTRON">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=K3ysTr0K3R&repo=CamTRON&theme=dark&hide_border=true">
</a>

<a href="https://github.com/K3ysTr0K3R/cPanelScanner">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=K3ysTr0K3R&repo=cPanelScanner&theme=dark&hide_border=true">
</a>

</p>

---

# Repository Portfolio

My GitHub contains a growing collection of:

```text
Security Scanners
        │
        ├── Network
        ├── Web
        ├── IoT
        ├── Cameras
        └── Network Appliances

Exploit PoCs
        │
        ├── RCE
        ├── Authentication Bypass
        ├── Command Injection
        ├── File Read
        └── Privilege Escalation

Research
        │
        ├── CVE Analysis
        ├── Vulnerability Research
        ├── Fingerprinting
        └── Security Automation
```

**Explore everything:**
https://github.com/K3ysTr0K3R?tab=repositories

---

# Collaboration

I'm open to collaborating with researchers, developers and security enthusiasts working on:

* Vulnerability research
* Exploit development
* Security tooling
* Reconnaissance
* Open-source security projects
* CVE research
* Defensive security
* Educational security labs

If you're building something interesting in cybersecurity, feel free to reach out.

---

# Contact

**Email:**
[jaredbrts175@gmail.com](mailto:jaredbrts175@gmail.com)

**GitHub:**
https://github.com/K3ysTr0K3R

**Instagram:**
https://instagram.com/k3ystr0k3r__1

**X / Twitter:**
https://twitter.com/K3ysTr0K3R_1

---

<div align="center">

### K3ysTr0K3R

`Cybersecurity Researcher`
`Ethical Hacker`
`Exploit Developer`
`Open-Source Security`

<br>

**Breaking things to understand how they work.**

</div>
