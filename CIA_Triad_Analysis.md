# CIA Triad Analysis

**Intern:** Ritu Raj
**Track:** Cyber Security
**Program:** Veda Technology Internship — Day 2 of 45
**Task:** CIA Triad Analysis

## Overview

The CIA Triad — **Confidentiality, Integrity, and Availability** — is the foundational model for information security. Each incident below illustrates a real-world failure of one of these three principles.

- **Confidentiality** — Ensuring information is accessible only to those authorized to see it.
- **Integrity** — Ensuring information remains accurate, complete, and unaltered except by authorized action.
- **Availability** — Ensuring systems and data are accessible to authorized users when needed.

## Five Real-World Examples

### 1. Equifax Data Breach (2017) — Confidentiality Failure
Attackers exploited an unpatched vulnerability in Apache Struts to access Equifax's systems, exposing the personal data (Social Security numbers, birth dates, addresses) of roughly 147 million people. This was a pure confidentiality breach: sensitive data was accessed by unauthorized parties, though the data itself wasn't altered or made unavailable.

### 2. Stuxnet Worm (2010) — Integrity Failure
Stuxnet infiltrated Iranian nuclear facility control systems and subtly altered the commands sent to centrifuges, causing them to spin at damaging speeds while feeding operators false "normal" readings. This is a classic integrity failure — the data monitoring the system was deliberately corrupted, undermining trust in what appeared to be legitimate readings.

### 3. Bangladesh Bank Heist (2016) — Integrity Failure
Hackers compromised the bank's SWIFT credentials and issued fraudulent transfer instructions, successfully moving $81 million out of the bank's account at the New York Fed. The integrity of the transaction records and authorization process was violated — the system processed instructions that appeared legitimate but were not.

### 4. Dyn DNS DDoS Attack (2016) — Availability Failure
The Mirai botnet flooded Dyn (a major DNS provider) with traffic, knocking major sites like Twitter, Netflix, Reddit, and Spotify offline for hours across the U.S. and Europe. No data was stolen or altered — the failure was purely one of availability, denying legitimate users access to services.

### 5. WannaCry Ransomware (2017) — Availability Failure
WannaCry exploited a Windows SMB vulnerability to encrypt files across 150+ countries, notably crippling the UK's National Health Service, forcing hospitals to cancel appointments and turn away patients. Encrypting data doesn't destroy or expose it, but it makes it completely inaccessible to legitimate users — an availability failure with serious real-world consequences.

## Interview Questions

**What is confidentiality?**
Confidentiality means restricting access to information so only authorized individuals or systems can view it. It's typically enforced through access controls, encryption, and authentication.

**What is integrity?**
Integrity means ensuring data is accurate and has not been tampered with, whether in storage, in transit, or during processing. It's enforced through checksums, digital signatures, version control, and audit logs.

**What is availability?**
Availability means ensuring systems and data are accessible to authorized users whenever needed. It's protected through redundancy, backups, failover systems, and defenses against denial-of-service attacks.

## Deliverables Checklist

- [x] CIA triad report
- [x] Five real-world examples with analysis
