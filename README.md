# Sigma Detection Engineering Repo

A collection of Sigma detection rules covering common attack techniques, mapped to MITRE ATT&CK and validated with Atomic Red Team in an isolated lab. CI enforces Sigma syntax via GitHub Actions.

## 🚧 Status

Active last updated April 26, 2026

- [x] Project plan
- [x] Atomic Red Team lab environment set up
- [ ] Brute force detection (T1110)
- [ ] Credential abuse detection (T1078)
- [ ] Suspicious PowerShell detection (T1059.001)
- [ ] Command execution detection (T1059)
- [ ] GitHub Actions Sigma syntax linting
- [ ] True/false positive validation table per rule

## Approach

Each rule will:

- Be written in Sigma YAML
- Map to a MITRE ATT&CK technique
- Be validated against an Atomic Red Team payload
- Track true positive / false positive results

## Tools

Sigma · Atomic Red Team · MITRE ATT&CK · GitHub Actions · sigma-cli
