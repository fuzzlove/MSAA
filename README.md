# macOS Security Audit Agent (MSAA)

> Turn a Mac into a security visibility workstation.

macOS Security Audit Agent (MSAA) is an open-source, local-first macOS security auditing, monitoring, and investigation platform designed to help users identify suspicious activity, preserve evidence, understand system changes, and improve overall security posture.

**Project Website:**  
https://fuzzlove.github.io/MSAA/

**GitHub Repository:**  
https://github.com/fuzzlove/macOS-Audit-Agent

**PyPI Package:**  
```bash
pip install macos-security-audit-agent
```

---

## Overview

MSAA is built to provide visibility into macOS security events without relying on cloud telemetry or enterprise licensing.

The project focuses on:

- Security auditing
- Intrusion detection
- System monitoring
- Investigation workflows
- Evidence preservation
- Apple security awareness
- Security hardening recommendations

All while keeping data local to the machine whenever possible.

---

## Features

### Security Auditing

Perform security audits of:

- Users and groups
- Admin accounts
- Persistence mechanisms
- LaunchAgents
- LaunchDaemons
- Login items
- Running processes
- Listening ports
- Security configuration
- File permissions
- System posture

---

### Intrusion Detection

Monitor for:

- USB device insertions/removals
- Bluetooth activity
- Lid open/close events
- Screen lock/unlock events
- Session activity
- Remote login changes
- Screen sharing changes
- Persistence changes
- New administrator accounts
- Suspicious process activity
- Trust score degradation

---

### Investigation Workflow

Designed to help answer:

- What changed?
- Why does it matter?
- What should I investigate first?
- What evidence should I preserve?

Features include:

- Review Queue
- Security Replay
- Flight Recorder
- Investigation Priorities
- Analyst Notes
- Evidence Snapshots

---

### Apple Security Forecast

Apple Security Forecast helps determine:

- Whether an Apple security update may apply
- Whether an update is known exploited
- Whether action is recommended

The feature is designed to reduce noise and focus on:

- macOS
- Safari
- WebKit
- Xcode
- Apple security advisories

rather than functioning as a generic CVE feed.

---

### Family & Safety Center

Provides guidance for:

- Parents
- Schools
- Libraries
- Caregivers
- Special-needs users

Including:

- Screen Time review
- Privacy settings review
- Content restrictions
- Remote access review
- Safety recommendations

---

### Evidence Preservation

Before cleanup or remediation actions, MSAA can create:

- Evidence snapshots
- Investigation reports
- Timeline exports
- Security findings exports

to reduce the risk of losing important information.

---

## Privacy

MSAA is designed to be:

- Local-first
- Privacy-focused
- Transparent

By default:

- No telemetry
- No cloud dependency
- No browser history inspection
- No private browsing inspection
- No cookie collection
- No keychain extraction
- No credential collection

---

## Installation

### Install from PyPI

```bash
pip install macos-security-audit-agent
```

Launch:

```bash
macos-security-audit-agent
```

---

### Install from Source

```bash
git clone https://github.com/fuzzlove/macOS-Audit-Agent.git

cd macOS-Audit-Agent

python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt

python3 -m mac_audit_agent.app
```

---

## Documentation

Visit:

https://fuzzlove.github.io/MSAA/

Additional documentation:

- Installation
- Features
- Security Model
- Apple Security Forecast
- Family & Safety
- Investigation Workflow
- Incident Response
- Release Notes

---

## Intended Users

MSAA may be useful for:

- Security researchers
- Incident responders
- Students
- Educators
- Families
- Small businesses
- Libraries
- Schools
- Public sector organizations
- Government evaluation teams

---

## Disclaimer

MSAA is a defensive security and auditing platform.

Findings are not proof of compromise.

Users should:

- Review evidence carefully
- Preserve logs when investigating incidents
- Verify findings independently
- Use the software only on systems they own or are authorized to assess

MSAA does not guarantee prevention, detection, or remediation of all threats.

---

## Contributing

Contributions, bug reports, feature requests, and pull requests are welcome.

Please review:

- CONTRIBUTING.md
- SECURITY.md
- CODE_OF_CONDUCT.md

before submitting changes.

---

## License

See LICENSE for details.

---

## Acknowledgements

Special thanks to:

- Objective-See Foundation
- MITRE
- NIST
- CISA
- Apple Security
- Open Source Security Community
- Researchers and contributors worldwide

for helping advance defensive security and public cybersecurity knowledge.

---

## Links

Website:
https://fuzzlove.github.io/MSAA/

Repository:
https://github.com/fuzzlove/macOS-Audit-Agent

PyPI:
https://pypi.org/project/macos-security-audit-agent/

Company:
https://liquidskysecurity.com
