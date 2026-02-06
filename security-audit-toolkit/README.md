# Security Audit Toolkit

A comprehensive, cross-platform security audit toolkit for developers, system administrators, and security professionals. Run red team assessments on your own systems to identify vulnerabilities before attackers do.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Linux%20%7C%20Windows-blue)]()

## Quick Start

### macOS
```bash
# Clone the repo
git clone https://github.com/michaelhauge/pertama-partners-resources.git
cd pertama-partners-resources/security-audit-toolkit

# Run full audit
chmod +x scripts/macos/*.sh
./scripts/macos/full-audit.sh
```

### Linux
```bash
# Clone the repo
git clone https://github.com/michaelhauge/pertama-partners-resources.git
cd pertama-partners-resources/security-audit-toolkit

# Run full audit
chmod +x scripts/linux/*.sh
./scripts/linux/full-audit.sh

# Or with auto-fix
./scripts/linux/full-audit.sh --fix
```

### Windows (PowerShell)
```powershell
.\scripts\windows\full-audit.ps1
```

## What This Toolkit Checks

### Network Security
- Open ports exposed to the network (not just localhost)
- Firewall status and configuration
- File sharing services (SMB, AFP, NFS)
- Remote access services (SSH, VNC, RDP)
- Guest access on shared resources

### Credential Security
- `.env` files with world-readable permissions
- API keys and tokens in common locations
- SSH key permissions
- Cloud credential files (AWS, GCP, Azure)
- Secrets accidentally committed to git

### System Hardening
- Disk encryption status
- Screen lock configuration
- Automatic updates
- Secure boot status

## Repository Structure

```
security-audit-toolkit/
├── scripts/           # Automated audit scripts
│   ├── macos/        # macOS-specific scripts
│   ├── linux/        # Linux-specific scripts
│   └── windows/      # Windows PowerShell scripts
├── checklists/       # Manual audit checklists
├── guides/           # How-to documentation
│   ├── beginners/    # Non-technical guides
│   ├── technical/    # Developer-focused guides
│   └── platform-specific/
├── templates/        # Reusable templates
└── examples/         # Sample outputs and reports
```

## Audit Scripts

| Script | Description |
|--------|-------------|
| `full-audit.sh` | Run all security checks |
| `network-audit.sh` | Check network exposure only |
| `credential-audit.sh` | Check credential security only |
| `remediate.sh` | Auto-fix common issues |

### Linux Script Features
- **Firewall detection**: UFW, firewalld, and iptables support
- **Service analysis**: Uses `ss` for network socket inspection
- **Permission checks**: `stat -c` for cross-distro compatibility
- **fail2ban**: Checks for SSH brute-force protection
- **LUKS**: Detects disk encryption status
- **SSH hardening**: Checks root login, password auth, key-only access
- **Automatic updates**: Detects unattended-upgrades (Debian/Ubuntu) and dnf-automatic (RHEL/Fedora)

## Checklists

- **[Red Team Checklist](checklists/red-team-checklist.md)** - Comprehensive 30+ point security audit
- **[Quick Security Check](checklists/quick-security-check.md)** - 5-minute basic assessment
- **[Pre-Deployment Checklist](checklists/pre-deployment.md)** - Before going to production
- **[Monthly Maintenance](checklists/monthly-maintenance.md)** - Recurring security tasks

## Guides

### For Beginners
- [What is a Security Audit?](guides/beginners/what-is-security-audit.md)
- [Understanding File Permissions](guides/beginners/understanding-permissions.md)
- [GUI Security Settings](guides/beginners/gui-security-settings.md)

### For Developers
- [Credential Rotation Best Practices](guides/technical/credential-rotation.md)
- [Secure Remote Access Setup](guides/technical/secure-remote-access.md)
- [.env File Security](guides/technical/env-file-security.md)
- [Secret Detection in Code](guides/technical/secret-detection.md)

### Platform-Specific
- [macOS Hardening Guide](guides/platform-specific/macos-hardening.md)
- [Linux Hardening Guide](guides/platform-specific/linux-hardening.md)
- [Windows Hardening Guide](guides/platform-specific/windows-hardening.md)

## Sample Output

```
=== SECURITY AUDIT REPORT ===
Date: 2024-01-15 14:30:00
System: macOS 14.2 (Sonoma)

[PASS] Firewall enabled
[PASS] Stealth mode enabled
[WARN] SSH exposed on all interfaces (0.0.0.0:22)
[FAIL] SMB guest access enabled
[PASS] All .env files have 600 permissions
[WARN] 2 credential files have 644 permissions

Summary: 2 PASS | 2 WARN | 1 FAIL
```

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Built from real-world security audits and red team assessments. Special thanks to the security community for sharing knowledge and best practices.

---

**Disclaimer:** This toolkit is for authorized security testing only. Always obtain proper authorization before running security audits on systems you don't own.
