# Pertama Partners Resources

A collection of tools, templates, and resources for technology consulting and advisory services.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Available Resources

| Resource | Description | Status |
|----------|-------------|--------|
| [Security Audit Toolkit](./security-audit-toolkit/) | Red team security assessments for developer workstations | Ready |
| [OpenClaw SEA Guide](./openclaw-sea-guide/) | Complete OpenClaw installation guide for Southeast Asia business leaders | Ready |
| [n8n SEA Guide](./n8n-sea-guide/) | Workflow automation guide - 90-98% cheaper than Zapier for SEA businesses | Ready |
| [CRM Migration Guide](./crm-migration-guide/) | CRM comparison & migration guide - Save $200-500/month switching from HubSpot/Salesforce | Ready |
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

## n8n Workflow Automation Guide for Southeast Asia

**A comprehensive guide for business leaders in Malaysia and Singapore to automate workflows and save 90-98% compared to Zapier.**

n8n is a powerful workflow automation platform that connects your business apps without code. Unlike Zapier (charges per step), n8n charges per execution, making it dramatically cheaper for complex workflows.

**Target Audience:**
- Small to medium businesses in SEA
- Budget-conscious users ($0-15/month vs Zapier's $30-75/month)
- Anyone tired of expensive SaaS subscriptions
- Completely self-service

**What's Included:**
- Step-by-step installation guides (Mac, Oracle Free, Contabo, DigitalOcean)
- Complete security documentation for PDPA compliance
- Cost comparison: n8n vs Zapier with ROI calculator
- 10 real SEA business use cases (lead capture, e-commerce, invoicing, etc.)
- WhatsApp & Telegram integration guides
- One-click installation scripts
- Health check and monitoring tools

**Quick Start:**
```bash
cd n8n-sea-guide
# Mac: Run one-click installer
bash scripts/install-mac.sh

# Or follow manual guides
open README.md
```

**Total Monthly Cost:** $0-15 (compare to Zapier's $30-75)

**Hosting Options:**
- Local Mac: Free testing ($0)
- Oracle Cloud Free: $0 hosting forever
- Contabo VPS: Best value (~$5.50/month)
- DigitalOcean: Easiest VPS ($24/month)
- n8n Cloud: Zero setup (€24/month)

**Real Savings Example:**
- 10-step workflow, 1,000 runs/month
- Zapier Professional: $75/month
- n8n self-hosted: $5.50/month
- **Annual savings: $834**

[View complete n8n guide →](./n8n-sea-guide/)

---

## CRM Migration Guide for Southeast Asia

**Comprehensive guide to help SEA businesses migrate from expensive CRMs (HubSpot, Salesforce) to affordable alternatives - Save $200-500/month**

This guide helps you choose the right CRM and migrate your data self-service in 2-4 hours, saving thousands annually.

**Target Audience**:
- Small to medium businesses (5-50 employees) in SEA
- Companies spending $150-1,000/month on HubSpot or Salesforce
- Budget-conscious teams looking for self-service migration
- Businesses needing WhatsApp integration

**What's Included**:
- CRM comparison matrix (Zoho, Freshsales, Pipedrive, Attio)
- Detailed pricing breakdown and 3-year TCO analysis
- Security documentation for PDPA compliance (SG, MY, ID, TH)
- Decision framework by industry and team size
- Python scripts for data cleanup and field mapping
- Migration validation scripts
- Export guides (HubSpot, Salesforce)
- Import guides (Zoho, Freshsales, Pipedrive)
- Post-migration checklist

**Quick Start**:
```bash
cd crm-migration-guide

# 1. Choose your CRM
open COMPARISON.md  # Compare features and pricing

# 2. Export and clean data
python3 scripts/data-cleanup.py hubspot_export.csv clean_data.csv

# 3. Map fields
python3 scripts/field-mapper.py --source hubspot --target zoho

# 4. Follow import guides in guides/ folder

# 5. Validate migration
bash scripts/migration-validator.sh
```

**Cost Savings Examples**:

| Migration Path | Old Cost | New Cost | Monthly Savings | Annual Savings |
|----------------|----------|----------|-----------------|----------------|
| HubSpot Pro → Zoho CRM | $900/mo | $230/mo | $670/mo | **$8,040/year** |
| HubSpot Pro → Freshsales | $900/mo | $390/mo | $510/mo | **$6,120/year** |
| Salesforce → Pipedrive | $800/mo | $290/mo | $510/mo | **$6,120/year** |

**Top CRM Recommendations**:
- **Best Value**: Zoho CRM Standard ($14/user) - Native WhatsApp integration
- **Easiest Migration**: Freshsales ($9-39/user) - One-click migration from HubSpot/Salesforce
- **Best for Sales Teams**: Pipedrive ($14-49/user) - Visual pipeline management
- **Best for Startups**: Attio ($6-29/user) - Flexible data model, 80% startup discount

**SEA-Specific Features**:
- WhatsApp Business API integration (Zoho CRM native support)
- LINE integration guides (for Thailand market)
- PDPA compliance documentation (Singapore, Malaysia, Thailand)
- Local payment methods (GIRO, bank transfers)
- Singapore/Malaysia data center options

**Migration Timeline**: 2-4 hours for self-service migration (10-person team)

[View complete CRM migration guide →](./crm-migration-guide/)

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
├── n8n-sea-guide/                # n8n Workflow Automation for SEA
│   ├── README.md                 # Main guide
│   ├── SECURITY.md               # Security & PDPA compliance
│   ├── PRICING.md                # Cost breakdown vs Zapier
│   ├── USE-CASES.md              # 10 real business examples
│   ├── FAQ.md                    # Common questions
│   ├── guides/                   # Installation guides (9 total)
│   ├── scripts/                  # Automation scripts
│   └── templates/                # Docker & env templates
│
├── crm-migration-guide/          # CRM Migration Guide for SEA
│   ├── README.md                 # Main guide
│   ├── COMPARISON.md             # CRM feature & pricing comparison
│   ├── PRICING.md                # Detailed pricing & TCO analysis
│   ├── SECURITY.md               # PDPA compliance & data protection
│   ├── FAQ.md                    # Common migration questions
│   ├── guides/                   # Migration guides
│   │   ├── 01-choosing-crm.md    # Decision framework
│   │   └── (export/import guides in progress)
│   ├── scripts/                  # Python & shell scripts
│   │   ├── data-cleanup.py       # Clean data before migration
│   │   ├── field-mapper.py       # Map fields between CRMs
│   │   └── migration-validator.sh # Verify migration success
│   └── templates/                # Checklists & mapping templates
│       ├── migration-checklist.md
│       └── field-mapping.csv
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
