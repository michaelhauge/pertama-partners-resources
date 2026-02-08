# Pertama Partners Resources

A collection of tools, templates, and resources for technology consulting and advisory services.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Available Resources

### AI & Automation
| Resource | Description | Status |
|----------|-------------|--------|
| [AI Implementation Playbook](./ai-implementation-playbook/) | 10 proven AI use cases with ROI analysis, tools comparison, and 30-Day Pilot plan | Ready |
| [AI Model Selection Guide](./ai-model-selection-guide/) | Navigate the AI provider landscape (OpenAI, Anthropic, Google, DeepSeek) — choose the right models | Ready |
| [AI Tooling Security Guide](./ai-tooling-security-guide/) | Safely use AI tools (Claude Code skills, MCP servers, browser extensions) without exposing your company | Ready |
| [AI Project Knowledge Guide](./ai-project-knowledge-guide/) | AI-powered project management, knowledge capture, and team workflow automation | Ready |
| [n8n SEA Guide](./n8n-sea-guide/) | Workflow automation — save 90-98% vs Zapier ($5.50/mo vs $75/mo) | Ready |
| [OpenClaw SEA Guide](./openclaw-sea-guide/) | Open-source AI assistant on your own machine ($5-25/month total cost) | Ready |

### Business Operations
| Resource | Description | Status |
|----------|-------------|--------|
| [B2B Sales Playbook SEA](./b2b-sales-playbook-sea/) | Sales strategy with country-by-country cultural selling guides for SG, MY, ID, TH, VN, PH | Ready |
| [Customer Success Guide SEA](./customer-success-guide-sea/) | B2B SaaS customer success framework for Southeast Asia | Ready |
| [Founder's Scaling Guide](./founder-scaling-guide/) | Scale from $1M to $10M ARR in Southeast Asia — operations, hiring, tech stack, fundraising | Ready |
| [CRM Migration Guide](./crm-migration-guide/) | Migrate from HubSpot/Salesforce to affordable alternatives — save $200-500/month | Ready |
| [SaaS Cost Optimization](./saas-optimization-guide/) | Reduce SaaS spend by 30-50% through audit, consolidation, and negotiation | Ready |
| [Remote Team Operations](./remote-team-operations/) | Managing distributed teams across SEA time zones | Ready |
| [Quick-Win Templates](./quick-win-templates/) | 40+ copy-paste ready templates: checklists, comparisons, one-pagers | Ready |

### Security & Compliance
| Resource | Description | Status |
|----------|-------------|--------|
| [Security Audit Toolkit](./security-audit-toolkit/) | Red team security assessments for developer workstations (macOS, Linux) | Ready |
| [CISO Security Guide](./ciso-security-guide/) | Enterprise security framework for IT leaders — 90-Day Security Sprint | Ready |
| [SMB Cybersecurity Guide](./smb-cybersecurity-guide/) | Practical cybersecurity for small businesses without IT departments | Ready |

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

## SaaS Stack Audit & Optimization Guide

**Comprehensive guide to help businesses reduce SaaS spend by 30-50% - Save $15,000-50,000 per year**

This guide provides a 4-step audit process to eliminate SaaS waste, consolidate overlapping tools, and negotiate better rates.

**Target Audience**:
- Small to medium businesses (10-100 employees)
- Companies spending $500-5,000/month on SaaS tools
- EO/YPO members looking to optimize tech stack
- Anyone tired of SaaS sprawl and overpriced renewals

**What's Included**:
- Complete 4-step audit methodology (Discover → Analyze → Optimize → Govern)
- Tool comparison matrix with 50+ alternatives and cost savings
- Consolidation strategies (all-in-one platforms vs category champions)
- Vendor negotiation playbook with proven tactics
- 5 ready-to-use email templates for negotiations
- Automated renewal tracking script
- Governance framework to prevent future sprawl
- Annual review checklist

**Quick Start**:
```bash
cd saas-optimization-guide

# 1. Build inventory
open guides/01-inventory.md  # Download template, gather data

# 2. Score tools
open guides/02-usage-analysis.md  # Use 5-dimension framework

# 3. Optimize
open CONSOLIDATION.md  # Merge overlapping tools
open NEGOTIATION.md    # Get better pricing

# 4. Prevent future sprawl
open guides/05-governance.md  # Set up policies
```

**Expected Savings Examples**:

| Company Size | SaaS Spend | Expected Savings | Annual Savings |
|--------------|------------|------------------|----------------|
| 10-25 employees | $800-2,000/mo | $240-800/mo (30-40%) | **$2,880-9,600/year** |
| 25-50 employees | $2,000-4,000/mo | $800-1,600/mo (40-45%) | **$9,600-19,200/year** |
| 50-100 employees | $4,000-8,000/mo | $1,600-3,500/mo (40-50%) | **$19,200-42,000/year** |

**Top Savings Opportunities**:
- **Cancel unused tools**: 0% utilization, still billing ($200-500/month typical)
- **Consolidate overlaps**: 3 project management tools → 1 ($400-1,200/month saved)
- **Negotiate renewals**: 15-30% discount on major tools ($300-1,000/month saved)
- **All-in-one platforms**: Replace 10-40 tools with Zoho ONE/Microsoft 365 (60-80% savings)

**Common Consolidations**:
- Asana + Monday + Trello → ClickUp (Save $400/month)
- Zendesk + Intercom → Freshdesk (Save $1,260/month)
- Slack + Zoom → Microsoft Teams (Save $295/month, already paying for Microsoft 365)
- HubSpot → Freshsales (Save $510/month)

**Time Required**: 8-16 hours over 2-4 weeks for full audit
**ROI**: 10-20x the time invested
**Ongoing Maintenance**: 2-4 hours/quarter to sustain savings

**Automation Tools**:
- `renewal-tracker.py` - Automated email reminders 60 days before renewals
- CSV templates for inventory and renewal tracking
- Scoring framework spreadsheet

[View complete SaaS optimization guide →](./saas-optimization-guide/)

---

## AI Implementation Playbook for Business Leaders

**Practical guide to implementing AI in your business - 10 proven use cases delivering 10-100x ROI in 30-90 days**

This playbook helps non-technical business leaders identify, implement, and measure AI opportunities that deliver real results.

**Target Audience**:
- CEOs and business owners (non-technical) of $1M-50M companies
- Operations managers looking to automate workflows
- Marketing/Sales/Support leaders wanting efficiency gains
- Anyone new to AI but needing practical business applications

**What's Included**:
- 10 AI use cases with clear ROI (customer support, sales, content, research, meetings, documents, recruitment, training, data analysis, e-commerce)
- AI tool comparison matrix (ChatGPT, Claude, Gemini, Copilot, specialized tools)
- Security & privacy framework (GDPR, HIPAA, data classification)
- 30-Day AI Pilot implementation plan
- Expected savings by company size

**Quick Start**:
```bash
cd ai-implementation-playbook

# 1. Find your opportunities
open USE-CASES.md  # Review 10 use cases, pick top 3

# 2. Choose tools
open TOOLS.md  # Compare AI tools for your use cases

# 3. Understand security
open SECURITY.md  # Data privacy and compliance

# 4. Implement
# Follow 30-Day AI Pilot in README.md
```

**Expected Results by Company Size**:

| Company Size | Time Saved/Week | Annual Value | AI Tool Costs | ROI |
|--------------|-----------------|--------------|---------------|-----|
| 5-10 employees | 10-20 hours | $30K-60K | $500-1,500/year | **20-120x** |
| 10-25 employees | 30-50 hours | $90K-150K | $1,500-3,500/year | **25-100x** |
| 25-50 employees | 60-120 hours | $180K-360K | $3,000-10,000/year | **18-120x** |

**Top Use Cases (Highest ROI)**:
1. **Customer Support** - AI drafts responses, 40-60% time savings
2. **Sales Enablement** - Personalized emails, 30-50% more outreach
3. **Content Creation** - 10x blog/social output with AI assistance
4. **Meeting Notes** - Automatic transcription, 80-95% time savings
5. **Product Descriptions** - 100x faster e-commerce catalog creation

**Implementation Framework**:
- **Phase 1 (Week 1-4)**: Quick wins with ChatGPT Plus/Claude Pro ($20/month)
- **Phase 2 (Month 2-3)**: Process integration with templates and team training
- **Phase 3 (Month 4-6)**: Custom solutions and automation workflows

**Tools Comparison**:
- **ChatGPT Plus** ($20/month) - Best all-around, web search, data analysis, image generation
- **Claude Pro** ($20/month) - Best for long documents, writing quality, privacy-focused
- **Specialized**: Otter.ai ($10/mo for meetings), Jasper ($49/mo for marketing), Midjourney ($30/mo for images)

**Security Framework**:
- Data classification guide (Public/Internal/Confidential/Restricted)
- Compliance by industry (Healthcare HIPAA, Finance SOC2, Legal privilege)
- Enterprise vs consumer AI tool comparison
- AI usage policy template

**Time Required**:
- Setup: 2-3 hours
- First use case: 1 week
- Team rollout: 30 days
- ROI measurement: Ongoing

**Status**: Complete
- ✅ README.md - Main guide and 30-Day Pilot
- ✅ USE-CASES.md - 10 use cases with ROI
- ✅ TOOLS.md - AI tool comparison
- ✅ SECURITY.md - Data privacy and compliance
- ✅ ADOPTION.md - Team adoption strategies
- ✅ PROMPT-LIBRARY.md - Ready-to-use prompts
- ✅ 10 detailed use case guides in use-cases/
- ✅ 4 policy/training templates in templates/
- ✅ ROI calculator script

[View complete AI implementation playbook →](./ai-implementation-playbook/)

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
├── saas-optimization-guide/      # SaaS Stack Audit & Optimization
│   ├── README.md                 # Main guide & quick start
│   ├── AUDIT-PROCESS.md          # 4-step methodology
│   ├── ALTERNATIVES.md           # 50+ tool alternatives with savings
│   ├── CONSOLIDATION.md          # Strategic consolidation approaches
│   ├── NEGOTIATION.md            # Vendor negotiation playbook
│   ├── FAQ.md                    # Common questions
│   ├── guides/                   # Step-by-step guides (6 total)
│   │   ├── 01-inventory.md       # Build SaaS inventory
│   │   ├── 02-usage-analysis.md  # Score tools (5-dimension framework)
│   │   ├── 03-consolidation.md   # Merge overlapping tools
│   │   ├── 04-negotiation.md     # Negotiate better rates
│   │   ├── 05-governance.md      # Prevent future sprawl
│   │   └── 06-annual-review.md   # Yearly audit checklist
│   ├── scripts/                  # Automation scripts
│   │   └── renewal-tracker.py    # Automated renewal reminders
│   └── templates/                # Tracking templates
│       ├── saas-inventory.csv    # Inventory spreadsheet
│       ├── renewal-calendar.csv  # Renewal tracking
│       └── negotiation-emails.md # 5 email templates
│
├── ai-implementation-playbook/   # AI Implementation for Business
│   ├── README.md                 # Main guide & 30-Day AI Pilot
│   ├── USE-CASES.md              # 10 AI use cases with ROI
│   ├── TOOLS.md                  # AI tool comparison matrix
│   ├── SECURITY.md               # Data privacy & compliance
│   ├── guides/                   # (Planned) Implementation guides
│   ├── use-cases/                # (Planned) Detailed use case guides
│   ├── templates/                # (Planned) Prompt templates & policies
│   └── scripts/                  # (Planned) Automation scripts
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

Open source resources maintained by Pertama Partners. Contributions welcome — see individual guides for details.

---

## License

MIT License - See [LICENSE](LICENSE) for details.

---

*Maintained by [Pertama Partners](https://pertama.partners)*
