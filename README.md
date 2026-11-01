# linux-ethical-hacking-practice
Ethical Hacking Practice: an authorized local network assessment using Nmap, Nessus, and Metasploit.

## Local Network Vulnerability Assessment

This repository documents an authorized, educational review of a local lab network using Nmap, Metasploit Framework, and Nessus. It records the available evidence, explains what it supports, and identifies the results that still need to be collected before the assessment can be called complete.

> **Assessment status: In progress.** The available screenshots support a preliminary Nmap host-discovery result and show Metasploit module research. The Nessus image supplied is a course example, not a scan of this network. Actual Nessus findings and severity totals are therefore not available and are not claimed.

## Goals

- Discover active hosts on an authorized local network.
- Identify open ports and services with Nmap.
- Research potential service risks using Metasploit module information.
- Assess hosts with Nessus and document verified findings and mitigations.

## Scope and authorization

- **Environment:** Personal/training lab network
- **Scope:** Local network; exact identifiers are withheld from this public repository
- **Authorization:** Testing is limited to systems owned by the learner or explicitly authorized for assessment
- **Assessment date:** Not confirmed in the supplied report

## Tools and method

1. **Nmap** — host discovery and service/version enumeration.
2. **Metasploit Framework** — research of modules relevant to observed services. A search result alone does not confirm that a host is vulnerable or that an exploit succeeded.
3. **Nessus** — intended vulnerability scan and severity review. The supplied Nessus screenshot is labeled as a sample in the course material, so it is not used as evidence of this assessment.

## Preliminary results

The available Nmap screenshot reports **3 hosts up** in the scanned range. The PDF also contains screenshots of a service scan and Metasploit searches. Exact service details are not transcribed here because the small embedded terminal screenshots are not sufficiently legible to verify every port and version reliably.

| Measure | Current result |
| --- | --- |
| Active hosts reported by Nmap | 3 |
| Open ports and services | Not reliably transcribable from supplied screenshots; see `report/Ethical_Hacking_Answers.md` |
| Nessus critical findings | Not available: actual scan results not supplied |
| Nessus high findings | Not available: actual scan results not supplied |
| Nessus medium findings | Not available: actual scan results not supplied |
| Nessus low findings | Not available: actual scan results not supplied |

## Repository contents

- [`report/Ethical_Hacking_Answers.md`](report/Ethical_Hacking_Answers.md) — organized assessment answers and evidence limitations.
- [`evidence/README.md`](evidence/README.md) — what genuine, sanitized screenshots to add.
- [`scans/README.md`](scans/README.md) — guidance for documenting scan details safely.

## Completion steps

1. Add the actual Nmap output or legible screenshots and verify the open ports, services, and versions.
2. Complete the Nessus scan on the authorized hosts.
3. Record the severity totals from the completed Nessus report and investigate the individual findings.
4. Add sanitized screenshots of the actual scans and document practical remediation steps.

## Privacy and responsible use


This project is for authorized defensive learning. Before publishing evidence, review it for private IP addresses, MAC addresses, public IPs, usernames, hostnames, credentials, tokens, and personal information. Never publish passwords, secrets, or unredacted vulnerability exports.
