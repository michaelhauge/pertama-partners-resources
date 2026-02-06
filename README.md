# Pertama Partners Resources

A collection of tools, templates, and resources for technology consulting and advisory services.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Available Resources

| Resource | Description | Status |
|----------|-------------|--------|
| [Security Audit Toolkit](./security-audit-toolkit/) | Red team security assessments for developer workstations | Ready |
| [OpenClaw SEA Guide](./openclaw-sea-guide/) | Complete OpenClaw installation guide for Southeast Asia business leaders | Ready |
| *More coming soon...* | | |

---

## Security Audit Toolkit

Comprehensive security audit scripts and checklists for macOS, Linux, and Windows.

**Quick Start:**
```bash
cd security-audit-toolkit
./scripts/macos/full-audit.sh
```

**Includes:**
- Automated audit scripts
- Red team checklists
- Credential rotation guides
- Pre-commit hooks for secret detection

[View full documentation →](./security-audit-toolkit/)

---

## OpenClaw Installation Guide for Southeast Asia

**A comprehensive guide for business leaders in Malaysia and Singapore to safely install and use OpenClaw.**

OpenClaw is a free, open-source AI assistant (150,000+ GitHub stars) that runs on your computer and connects to WhatsApp, Telegram, and other messaging apps for business automation.

**Target Audience:**
- Non-technical business leaders in SEA
- Budget-conscious users ($5-25/month total cost)
- Security-conscious professionals
- Completely self-service

**What's Included:**
- Step-by-step installation guides (Mac, VPS options)
- Complete security documentation addressing all common fears
- Transparent pricing breakdown and cost calculator
- LLM provider comparisons (Kimi K2, DeepSeek, Qwen, Claude)
- WhatsApp & Telegram integration guides
- Real business use cases for SEA leaders
- One-click installation scripts
- Health check and monitoring tools

**Quick Start:**
```bash
cd openclaw-sea-guide
# Mac: Run one-click installer
bash scripts/install-mac.sh

# Or follow manual guides
open README.md
```

**Total Monthly Cost:** $5-25 depending on choices

**Hosting Options:**
- Local Mac: Maximum privacy ($5-20/month)
- Oracle Cloud Free: $0 hosting forever ($5-20/month total)
- DigitalOcean: Easiest VPS ($11-26/month)
- Contabo: Best value VPS ($10-25/month)

[View complete OpenClaw guide →](./openclaw-sea-guide/)

---

## Repository Structure

```
pertama-partners-resources/
├── README.md                      # This file
├── LICENSE                        # MIT License
│
├── security-audit-toolkit/        # Security assessments
│   ├── scripts/                   # Automated audit scripts
│   ├── checklists/               # Manual checklists
│   ├── guides/                   # How-to documentation
│   └── templates/                # Report templates
│
├── openclaw-sea-guide/           # OpenClaw for SEA businesses
│   ├── README.md                 # Main guide
│   ├── SECURITY.md               # Security concerns addressed
│   ├── PRICING.md                # Cost breakdown
│   ├── USE-CASES.md              # Business automation examples
│   ├── FAQ.md                    # Common questions
│   ├── guides/                   # Installation guides (8 total)
│   ├── scripts/                  # Automation scripts
│   └── templates/                # Configuration templates
│
├── shared/                        # Shared resources
│   └── (common templates, scripts)
│
└── [future-tools]/               # Additional tools TBD
```

---

## Planned Resources

- [ ] **Due Diligence Toolkit** - Tech DD checklists and templates
- [ ] **Startup Tech Assessment** - CTO-as-a-Service evaluation frameworks
- [ ] **Investment Memo Templates** - Standardized analysis formats
- [ ] **Market Research Tools** - Industry analysis scripts
- [ ] **Integration Playbooks** - Post-acquisition tech integration guides

---

## Usage

### Clone the Repository
```bash
git clone https://github.com/michaelhauge/pertama-partners-resources.git
cd pertama-partners-resources
```

### Use a Specific Tool
```bash
# Security Audit
cd security-audit-toolkit
./scripts/macos/full-audit.sh

# Future tools will have similar structure
cd [tool-name]
./scripts/[script].sh
```

---

## Contributing

This is a private resource repository for Pertama Partners. For questions or suggestions, contact the maintainer.

---

## License

MIT License - See [LICENSE](LICENSE) for details.

---

*Maintained by [Pertama Partners](https://pertama.partners)*
