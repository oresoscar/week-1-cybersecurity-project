# Week 1 – Cybersecurity Lab Setup (Phase 1)

## NetworkWalks Cybersecurity & Ethical Hacking Internship

This repository documents **Week 1, Project **: setting up a
cybersecurity testing laboratory environment using Oracle VirtualBox and Kali Linux.

### Scope

This repository covers **Phase 1 only**. The assignment defines six Phase 1 steps:

1. Download and install 7-Zip.
2. Download and install Oracle VirtualBox.
3. Configure a VirtualBox NAT Network using the `10.0.0.0/24` subnet.
4. Download and import Kali Linux into VirtualBox.
5. Configure the Kali Linux IP address as `10.0.0.2/24`.
6. Take a snapshot of the Kali Linux virtual machine.

The assignment also requires Kali Linux to have Internet access. Clipboard/file
drag-and-drop and a shared `/downloads` folder are part of the lab setup
requirements.

> **Note:** Phase 2 is intentionally excluded. It covers additional Windows,
> Android, inter-VM ping testing, and snapshots for future/optional tasks.

## Lab Configuration

| Item | Configuration |
|---|---|
| Virtualization platform | Oracle VirtualBox |
| Security testing machine | Kali Linux |
| Network type | NAT Network |
| Network | `10.0.0.0/24` |
| Kali Linux IP | `10.0.0.2/24` |
| Internet access | Required |
| Shared folder | `/downloads` |
| Clipboard | Enabled |
| File drag-and-drop | Enabled |
| VM snapshot | Required |

## Project Objectives

- Build a controlled environment for cybersecurity and ethical-hacking practice.
- Configure an isolated NAT Network for the laboratory.
- Prepare Kali Linux as the attacking/security-testing machine.
- Verify the required IP configuration and Internet connectivity.
- Preserve the working VM state using a VirtualBox snapshot.

## Evidence

The `screenshots/` directory is reserved for personal evidence captured
during the implementation.

Recommended evidence:

- `11.png`
- `12.png`
- `13.png`
- `14.png`
- `15.png`
- `16.png`
- `17.png`
-  `18.png`
- `19.png`
- `20.png`
- `21.png`
- `22.png`

**Important:** Replace the placeholder evidence with your own screenshots.
Do not claim a step was completed until you have captured evidence of it.

## Suggested Kali Verification Commands

After configuring Kali, the following commands can be used to document the
configuration:

```bash
ip addr
ip route
ping -c 4 8.8.8.8
```

Use only commands appropriate to your own lab and assignment.

## Completion Checklist

- [ ] 7-Zip installed
- [ ] VirtualBox installed
- [ ] NAT Network created with `10.0.0.0/24`
- [ ] Kali Linux imported
- [ ] Kali configured with `10.0.0.2/24`
- [ ] Kali Internet access verified
- [ ] Clipboard enabled
- [ ] File drag-and-drop enabled
- [ ] `/downloads` shared folder configured
- [ ] Kali VM snapshot created
- [ ] Evidence screenshots added

## Learning Outcome

The completed Phase 1 environment provides a controlled foundation for
future cybersecurity and ethical-hacking laboratory exercises.

## Author

**ORES OSCAR**

Cybersecurity & Ethical Hacking Internship  
NetworkWalks Academy

## Reference

Week 1 Project , NetworkWalks Academy — Lab Setup:
VirtualBox and Kali Linux.
