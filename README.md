<p align="center"><img src="assets/banner.svg" alt="Cedric Kofi Ahiato – IT Support & System Administration" width="100%"></p>

<p align="center">
  <a href="mailto:info.cedricahiato@gmail.com"><img src="https://img.shields.io/badge/E--Mail-info.cedricahiato%40gmail.com-0B1F3A?style=flat-square&logo=gmail&logoColor=white" alt="E-Mail"></a>
  <!-- TODO: add your LinkedIn: <a href="https://www.linkedin.com/in/YOUR-PROFILE"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a> -->
  <img src="https://img.shields.io/badge/Location-Erfurt%2C_Germany-123B6D?style=flat-square&logo=googlemaps&logoColor=white" alt="Erfurt, Germany">
  <img src="https://img.shields.io/badge/Available-immediately-2E7D32?style=flat-square" alt="Available immediately">
</p>

## About me

IT professional with an **M.Sc. in Applied Computer Science** and hands-on experience in **1st and 2nd-level support** and **system administration**: Active Directory, Windows and Linux servers, VMware and Hyper-V, DNS, with tickets tracked in Jira. I'm currently training as an **IT Support Specialist (IHK)**.

This GitHub is my lab portfolio. In it I build and document the IT of a small fictional company, *NordLicht Handel GmbH* (25 staff), end to end: from the first domain controller to a major incident review.

> [!NOTE]
> **Kurzfassung (DE):** IT-Fachkraft (M.Sc. Angewandte Informatik) mit Erfahrung im 1st-/2nd-Level-Support und in der Systemadministration. Hier dokumentiere ich praxisnahe Laborprojekte zu Active Directory, Microsoft 365, Intune, PowerShell, Netzwerk, Linux und IT-Service-Management. Deutsch C1 · Englisch C2 · verfügbar ab sofort.

## Portfolio: 10 projects, one company

```mermaid
flowchart LR
    subgraph Infrastructure
        P01["01 Homelab"] --> P02["02 AD & GPO"] --> P03["03 PowerShell"]
        P01 --> P08["08 Network"]
        P01 --> P09["09 Linux, monitoring,<br/>backup"]
    end
    subgraph Cloud["Modern workplace"]
        P04["04 M365 & Entra ID"] --> P05["05 Intune"]
    end
    subgraph Service["Service management"]
        P06["06 Help desk"] --> P07["07 Knowledge base"]
    end
    P03 --> P04
    P02 & P05 & P09 --> P06
    P06 & P09 --> P10["10 Major incident<br/>capstone"]
    classDef n fill:#0B1F3A,stroke:#5FB3FF,color:#fff
    class P01,P02,P03,P04,P05,P06,P07,P08,P09 n
    style P10 fill:#B42318,stroke:#F04438,color:#fff
```

| | Project | What it shows | Stack |
|:-:|---|---|---|
| **01** | [**Homelab Build**](https://github.com/BigDougCed/01-homelab-build) | Hyper-V lab: Windows Server 2022 DC (AD DS, DNS, DHCP), Windows 11 clients, Ubuntu, built by script | Hyper-V · PowerShell |
| **02** | [**Active Directory & Group Policy**](https://github.com/BigDougCed/02-active-directory-gpo) | OU design, AGDLP permissions, file shares, 8 documented GPOs | AD · GPO · NTFS |
| **03** | [**PowerShell AD Automation**](https://github.com/BigDougCed/03-powershell-ad-automation) | Onboarding/offboarding from HR CSV, help desk password reset, AD hygiene report, Pester tests + CI | PowerShell · Pester |
| **04** | [**Microsoft 365 & Entra ID**](https://github.com/BigDougCed/04-m365-entra-id) | Group-based licensing, MFA, Conditional Access baseline, Exchange Online, Graph scripts | Entra ID · Graph |
| **05** | [**Intune Endpoint Management**](https://github.com/BigDougCed/05-intune-endpoint-management) | Compliance, BitLocker, update rings, Win32 app packaging, remediations, Autopilot | Intune · Autopilot |
| **06** | [**Help Desk Ticketing**](https://github.com/BigDougCed/06-helpdesk-ticketing-zammad) | Zammad with SLAs P1–P4 and **15 fully documented tickets** (DE/EN communication) | Zammad · ITIL |
| **07** | [**IT Knowledge Base**](https://github.com/BigDougCed/07-it-knowledge-base) | 7 German end-user guides, 3 English technician runbooks | Technical writing |
| **08** | [**Network Lab**](https://github.com/BigDougCed/08-network-lab-packet-tracer) | VLANs, inter-VLAN routing, DHCP, NAT, ACLs, port security, troubleshooting scenarios | Cisco IOS |
| **09** | [**Linux, Monitoring & Backup**](https://github.com/BigDougCed/09-linux-monitoring-backup) | Server hardening, Uptime Kuma alerting, restic 3-2-1 backups with restore tests | Ubuntu · Bash · Docker |
| **10** | [**Major Incident Capstone**](https://github.com/BigDougCed/10-major-incident-capstone) | P1 outage with two root causes: timeline, status updates, post-incident review | ITIL · AD · Kerberos |

## Skills

**Service desk & ITSM**<br>
<img src="https://img.shields.io/badge/1st%2F2nd_Level_Support-0B1F3A?style=flat-square" alt="Support"> <img src="https://img.shields.io/badge/ITIL_4-4B2C83?style=flat-square" alt="ITIL"> <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white" alt="Jira"> <img src="https://img.shields.io/badge/Zammad-E16E2C?style=flat-square" alt="Zammad"> <img src="https://img.shields.io/badge/SLAs_%26_Escalation-123B6D?style=flat-square" alt="SLAs">

**Microsoft**<br>
<img src="https://img.shields.io/badge/Windows_10%2F11-0078D4?style=flat-square&logo=windows11&logoColor=white" alt="Windows"> <img src="https://img.shields.io/badge/Windows_Server-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Windows Server"> <img src="https://img.shields.io/badge/Active_Directory-0A4D8C?style=flat-square&logo=microsoft&logoColor=white" alt="AD"> <img src="https://img.shields.io/badge/Group_Policy-0A4D8C?style=flat-square" alt="GPO"> <img src="https://img.shields.io/badge/Microsoft_365-D83B01?style=flat-square&logo=microsoft&logoColor=white" alt="M365"> <img src="https://img.shields.io/badge/Entra_ID-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Entra ID"> <img src="https://img.shields.io/badge/Intune-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Intune"> <img src="https://img.shields.io/badge/Exchange_Online-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white" alt="Exchange">

**Infrastructure**<br>
<img src="https://img.shields.io/badge/VMware_vSphere-607078?style=flat-square&logo=vmware&logoColor=white" alt="VMware"> <img src="https://img.shields.io/badge/Hyper--V-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Hyper-V"> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"> <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Ubuntu"> <img src="https://img.shields.io/badge/RHEL%2FCentOS-EE0000?style=flat-square&logo=redhat&logoColor=white" alt="RHEL"> <img src="https://img.shields.io/badge/TCP%2FIP_·_DNS_·_DHCP-123B6D?style=flat-square" alt="Networking"> <img src="https://img.shields.io/badge/Cisco_IOS-1BA0D7?style=flat-square&logo=cisco&logoColor=white" alt="Cisco"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">

**Scripting, data & cloud**<br>
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell"> <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"> <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"> <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure"> <img src="https://img.shields.io/badge/Git_%26_GitHub_Actions-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">

## Experience at a glance

| Period | Role | Where |
|---|---|---|
| 2026 – 2027 | IT Support Specialist (IHK), training | Syntax Institut GmbH |
| 2024 – 2025 | Student event coordinator, IT user support | Hochschule Schmalkalden |
| 2020 – 2025 | M.Sc. Applied Computer Science | Hochschule Schmalkalden |
| 2017 – 2018 | System Administrator (1st/2nd level, AD, Windows/Linux servers, VMware) | Inpath Technologies, Accra |
| 2015 – 2017 | Tech Support | National Service Secretariat, Accra |

**Languages:** German C1 · English C2

---

<p align="center"><sub>All lab projects use a fictional company and contain no real customer data.</sub></p>
