<div align="center">

<!-- BANNER IMAGE — upload IamG2_banner.png to your repo root and it will display here -->

<img src="https://github.com/G33l0/IamG2/blob/main/IamG2%20banner.png" alt="IamG2 Banner" width="100%"/>

<br/><br/>

<!-- Animated typing role banner -->

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1000&color=FF0000&center=true&vCenter=true&width=750&lines=%F0%9F%94%B4+Offensive+Security+Engineer;%F0%9F%94%B4+Vulnerability+Scanner+Builder;%F0%9F%94%B4+OSINT+%26+Recon+Specialist;%F0%9F%94%B4+CVE+Hunter+%26+Exploit+Developer;%F0%9F%94%B4+Red+Team+Automation+Engineer" alt="Typing SVG" />

<br/>

<a href="https://github.com/g33l0">
  <img src="https://img.shields.io/badge/GitHub-g33l0-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://t.me/x0x0h33l0">
  <img src="https://img.shields.io/badge/Telegram-x0x0h33l0-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/>
</a>
<a href="mailto:obileyegideon@gmail.com">
  <img src="https://img.shields.io/badge/Email-obileyegideon@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/Focus-Offensive%20Security-FF0000?style=for-the-badge&logo=hackaday&logoColor=white"/>
<img src="https://img.shields.io/badge/Tools%20Built-4%20Deployed-brightgreen?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Tests%20Passing-104%2F104-00CC44?style=for-the-badge&logo=pytest&logoColor=white"/>
<img src="https://img.shields.io/badge/CVE%20Coverage-CVSS%209.9-CC0000?style=for-the-badge"/>

-----

> *“I don’t just find vulnerabilities — I build the tools that find them at scale.”*

</div>

-----

## 🧠 About Me

I’m an **Offensive Security Engineer** who specializes in building **automated reconnaissance and vulnerability scanning tools** used in real-world security assessments. My work sits at the intersection of red teaming, OSINT, and software engineering — I don’t just run scanners, I **build them**.

I operate a **security monitoring and consulting practice**, conducting structured vulnerability assessments across client domains, producing threat analysis reports, and delivering prioritized remediation guidance to both technical teams and executive stakeholders.

My tools are **deployed in production**, battle-tested against live environments, and engineered with a focus on **accuracy, low false-positive rates, and actionable output**.

```python
whoami = {
    "alias"     : "IamG2",
    "role"      : "Offensive Security Engineer & Tool Builder",
    "languages" : ["Python", "Bash"],
    "focus"     : ["Red Team Automation", "OSINT", "CVE Research", "Vuln Scanning"],
    "approach"  : "I build the tools — not just run them",
    "status"    : "Open to consulting engagements & contracts"
}
```

-----

## 🛠️ Custom Security Tools (Production-Deployed)

### 🔴 [EnvHunter](https://github.com/g33l0) `v4.8` — Environment File Exposure Scanner

> Detects exposed `.env` files across web targets with high accuracy and minimal false positives.

- **Smart redirect logic** — distinguishes legitimate HTTP→HTTPS upgrades from cPanel/hosting redirects
- **Mixed-case & camelCase key detection** — catches non-standard `.env` formats missed by other tools
- **Tuned detection thresholds** — optimized for shared hosting environments with timeout controls
- **Real-world impact**: Uncovers exposed database credentials, API keys, and secret tokens before attackers do

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![Status](https://img.shields.io/badge/Status-v4.8%20Deployed-brightgreen?style=flat-square)
![Type](https://img.shields.io/badge/Type-Exposure%20Scanner-red?style=flat-square)

-----

### 🔴 [RedHunter](https://github.com/g33l0) `v1.3` — Multi-CVE Vulnerability Scanner

> Automated scanner targeting high-severity CVEs across web stacks, with enterprise SAP coverage.

- **SAP Enterprise Detection** — CVE-2025-42957 (NetWeaver ICM, CVSS 9.9) & CVE-2025-42887 (Solution Manager, CVSS 9.9)
- **3-Gate Detection Pipeline**: HEAD reachability → body signature matching → confirm_absent verification
- **Telegram integration** — real-time alerting with HTML escaping, rate limiting, and vuln deduplication
- **104/104 tests passing** — rigorous test suite with zero false-positive tolerance
- **Deep FP audit** — 10 signature fixes + 10 Telegram bug fixes for production reliability

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![CVEs](https://img.shields.io/badge/CVEs-CVSS%209.9-red?style=flat-square)
![Tests](https://img.shields.io/badge/Tests-104%2F104-brightgreen?style=flat-square)
![Status](https://img.shields.io/badge/Status-v1.3%20Deployed-brightgreen?style=flat-square)

-----

### 🔴 [ShadowScraper](https://github.com/g33l0) — OSINT & Reconnaissance CLI

> Python CLI tool for deep OSINT reconnaissance and attack surface mapping from an attacker’s perspective.

- **Domain & IP enumeration** with precision regex (no false-matching IPs as domains)
- **IPv6 support** — complete coverage across all address families
- **Attacker-perspective output** — findings structured to highlight real exploitation paths
- Identifies: exposed `.git` directories, cPanel panels, `phpinfo()` debug pages, dependency file leaks, WordPress REST API user enumeration

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![OSINT](https://img.shields.io/badge/Type-OSINT%2FRecon-orange?style=flat-square)
![CLI](https://img.shields.io/badge/Interface-CLI-black?style=flat-square)

-----

### 🔴 [SpiderWeb Pro](https://github.com/g33l0) — Async Network Recon & Vuln Scanner

> High-performance async network reconnaissance tool for large-scale infrastructure assessments.

- **Async architecture** — concurrent scanning across multiple targets for speed at scale
- **SSL certificate extraction** — full cert field parsing, expiry tracking, and analysis
- **WHOIS integration** — multi-registry support beyond ARIN for global coverage
- **Service fingerprinting** — MariaDB binary greeting parsing, web server banners, custom signatures
- Produces structured vulnerability reports with prioritized remediation roadmaps

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![Async](https://img.shields.io/badge/Architecture-Async-purple?style=flat-square)
![Network](https://img.shields.io/badge/Type-Network%20Recon-blue?style=flat-square)

-----

## 🎯 What I Do For Clients

```
┌─────────────────────────────────────────────────────────────────────┐
│                        SERVICE OFFERINGS                            │
├─────────────────────────────────────────────────────────────────────┤
│  🔍  Vulnerability Scanning        Automated + manual assessments   │
│      & Assessment                  across client domains            │
│                                                                     │
│  🌐  OSINT Reconnaissance          Attack surface mapping,          │
│      & Recon                       exposed asset discovery          │
│                                                                     │
│  📋  Threat Analysis Reports       Structured findings with         │
│      & Remediation                 prioritized fix guidance         │
│                                                                     │
│  🔴  Red Team Automation           Custom tooling built for         │
│      & Tool Development            your specific environment        │
│                                                                     │
│  🛡️  Security Monitoring           Ongoing signed monitoring        │
│      Plans                         plans for client domains         │
│                                                                     │
│  ⚙️  Custom Scanner Development    Need a scanner for a specific    │
│                                    CVE or target class? I build it  │
└─────────────────────────────────────────────────────────────────────┘
```

-----

## 💼 Why Work With Me

|Capability                   |Detail                                                                                |
|-----------------------------|--------------------------------------------------------------------------------------|
|🏗️ **Tool Builder**           |I engineer custom scanners from scratch — production-grade, versioned, and tested     |
|🎯 **Low False Positives**    |Multi-gate detection logic with 104-test CI discipline and deep FP audits             |
|📊 **Business-Ready Reports** |Threat reports built for both technical teams and executive decision-makers           |
|⚡ **Production-Grade Code**  |Deployed tools with async design, rate limiting, deduplication, and Telegram alerting |
|🔄 **Continuous Iteration**   |Active versioned development (v4.8, v1.3) with changelog discipline                   |
|🏢 **Enterprise CVE Coverage**|SAP NetWeaver, SAP Solution Manager, WordPress, cPanel, and common web stacks         |
|🔬 **Attacker Mindset**       |All tooling outputs are structured to answer: *“What would an attacker do with this?”*|

-----

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=g33l0&show_icons=true&theme=dark&bg_color=0d0d0d&title_color=FF0000&icon_color=FF4444&text_color=ffffff&border_color=FF0000&count_private=true&include_all_commits=true"/>
&nbsp;
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=g33l0&layout=compact&theme=dark&bg_color=0d0d0d&title_color=FF0000&text_color=ffffff&border_color=FF0000"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=g33l0&theme=dark&background=0d0d0d&ring=FF0000&fire=FF4444&currStreakLabel=FF0000&sideLabels=ffffff&dates=888888&border=FF0000"/>

</div>

-----

## 📊 Threat Coverage Areas

<div align="center">

![Web App Security](https://img.shields.io/badge/-Web%20App%20Security-FF4444?style=for-the-badge)
![OSINT](https://img.shields.io/badge/-OSINT%20%26%20Recon-FF6600?style=for-the-badge)
![CVE Research](https://img.shields.io/badge/-CVE%20Research-CC0000?style=for-the-badge)
![Red Team](https://img.shields.io/badge/-Red%20Team%20Automation-880000?style=for-the-badge)
![SAP Security](https://img.shields.io/badge/-SAP%20Enterprise-AA0000?style=for-the-badge)
![WordPress](https://img.shields.io/badge/-WordPress%20Hardening-DD2222?style=for-the-badge)
![Network Recon](https://img.shields.io/badge/-Network%20Recon-FF2222?style=for-the-badge)
![Env Exposure](https://img.shields.io/badge/-.env%20Exposure%20Detection-CC2200?style=for-the-badge)
![SSL Analysis](https://img.shields.io/badge/-SSL%20Cert%20Analysis-BB1100?style=for-the-badge)
![Threat Reporting](https://img.shields.io/badge/-Threat%20Reporting-990000?style=for-the-badge)

</div>

-----

## 📬 Contact & Collaboration

> Available for **security consulting engagements**, **penetration testing contracts**, **custom tool development**, and **ongoing monitoring retainers**.

<div align="center">

|Channel   |Link                                                     |
|----------|---------------------------------------------------------|
|🐙 GitHub  |[github.com/g33l0](https://github.com/g33l0)             |
|✈️ Telegram|[@x0x0h33l0](https://t.me/x0x0h33l0)                     |
|📧 Email   |[obileyegideon@gmail.com](mailto:obileyegideon@gmail.com)|

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-g33l0-181717?style=for-the-badge&logo=github)](https://github.com/g33l0)
[![Telegram](https://img.shields.io/badge/Telegram-@x0x0h33l0-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/x0x0h33l0)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:obileyegideon@gmail.com)

<br/>

*Serious inquiries only. All engagements conducted under signed agreements.*

</div>

-----

<div align="center">

```
[ AUTHORIZED TESTING ONLY — ALL TOOLS USED ETHICALLY AND LEGALLY ]
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=2000&color=FF0000&center=true&vCenter=true&width=650&lines=Scanning+the+surface+others+ignore...;Building+tools+that+scale+beyond+manual+review...;Finding+what+attackers+find+%E2%80%94+before+they+do.;4+tools+deployed.+104+tests+passing.+0+excuses." alt="Footer typing" />

<br/>

<img src="https://komarev.com/ghpvc/?username=g33l0&color=FF0000&style=flat-square&label=Profile+Views"/>

</div>
