# SaaS Stack Audit & Optimization Guide

**Reduce your SaaS spend by 30-50% - Save $15,000-50,000 per year**

A comprehensive guide to help businesses audit their SaaS tools, eliminate waste, consolidate overlapping solutions, and negotiate better rates.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## The Problem

The average small-to-medium business uses **50-100+ SaaS tools** and spends **$500-5,000/month** on software subscriptions.

**30-40% of this spend is waste**:
- ❌ Unused licenses (employees left, features never used)
- ❌ Duplicate tools (3 project management tools, 2 CRMs)
- ❌ Overbuilt plans (Enterprise when Starter would suffice)
- ❌ Missing volume discounts (never asked for better pricing)
- ❌ Auto-renewals at full price (no negotiation)

**Example company** (50 employees, $3,500/month SaaS spend):
- Savings potential: $1,050-1,400/month
- Annual savings: **$12,600-16,800**
- 3-year savings: **$37,800-50,400**

---

## The Solution

This guide provides a **4-step audit process** to:

1. **Discover** - Build complete SaaS inventory
2. **Analyze** - Identify waste and redundancy
3. **Optimize** - Consolidate, negotiate, cancel
4. **Govern** - Prevent future SaaS sprawl

**Time required**: 2-4 weeks for full audit (8-16 hours of work)
**Typical savings**: 30-50% of current SaaS spend
**ROI**: 10-20x (pay back audit time in first quarter)

---

## Quick Self-Assessment

**Do you have SaaS sprawl?** Check if any of these apply:

- [ ] You can't list all the SaaS tools your company uses from memory
- [ ] You've discovered subscriptions still active for employees who left 6+ months ago
- [ ] You have 2+ tools in the same category (e.g., Asana + Monday + ClickUp)
- [ ] You're on "Enterprise" plans but use <20% of advanced features
- [ ] You haven't negotiated pricing in the last 12 months
- [ ] You renew annually without checking competitors
- [ ] You don't track which users actually log into each tool
- [ ] Your finance team doesn't have visibility into all software spend

**If you checked 3+**, you likely have 25-40% savings opportunity.
**If you checked 5+**, you likely have 40-50%+ savings opportunity.

---

## What You'll Save

### Real Examples

**Company A** - Tech startup, 35 employees:
- **Before**: $2,800/month across 47 SaaS tools
- **After**: $1,750/month across 28 tools
- **Savings**: $1,050/month (**$12,600/year**)
- **Actions**: Canceled 19 unused tools, consolidated project management (Asana + Monday + Trello → Notion), negotiated HubSpot renewal (15% off)

**Company B** - Professional services, 85 employees:
- **Before**: $6,200/month across 73 SaaS tools
- **After**: $3,500/month across 42 tools
- **Savings**: $2,700/month (**$32,400/year**)
- **Actions**: Switched to Zoho ONE (replaced 12 tools), negotiated Microsoft 365 (multi-year discount), canceled dormant integrations

**Company C** - E-commerce, 25 employees:
- **Before**: $1,900/month across 38 SaaS tools
- **After**: $1,100/month across 22 tools
- **Savings**: $800/month (**$9,600/year**)
- **Actions**: Downgraded Shopify plan, consolidated marketing tools (Mailchimp + HubSpot Marketing → Brevo), renegotiated shipping software

---

## Documentation Structure

### 📊 Core Process

| Document | What It Covers | When to Read |
|----------|----------------|--------------|
| [**AUDIT-PROCESS.md**](./AUDIT-PROCESS.md) | Complete 4-step methodology | **Read first** - your roadmap |
| [**ALTERNATIVES.md**](./ALTERNATIVES.md) | 50+ tool alternatives with cost savings | During consolidation planning |
| [**NEGOTIATION.md**](./NEGOTIATION.md) | Vendor negotiation tactics | Before renewal conversations |
| [**CONSOLIDATION.md**](./CONSOLIDATION.md) | Strategic consolidation approaches | When choosing all-in-one vs specialized |

### 📖 Step-by-Step Guides

| Guide | What It Covers | Time Required |
|-------|----------------|---------------|
| [**01-inventory.md**](./guides/01-inventory.md) | Build complete SaaS inventory | 2-4 hours |
| [**02-usage-analysis.md**](./guides/02-usage-analysis.md) | Identify unused licenses and features | 2-3 hours |
| [**03-consolidation.md**](./guides/03-consolidation.md) | Merge overlapping tools | 1-2 hours |
| [**04-negotiation.md**](./guides/04-negotiation.md) | Negotiate better rates | Ongoing |
| [**05-governance.md**](./guides/05-governance.md) | Prevent future sprawl | 1-2 hours setup |
| [**06-annual-review.md**](./guides/06-annual-review.md) | Yearly audit process | 4-6 hours/year |

### 🛠️ Tools & Templates

| Resource | Purpose | Usage |
|----------|---------|-------|
| [**saas-inventory.csv**](./templates/saas-inventory.csv) | Track all tools, costs, users, renewal dates | Fill out during discovery |
| [**negotiation-emails.md**](./templates/negotiation-emails.md) | 5 email templates for vendor negotiations | Copy/paste when negotiating |
| [**renewal-calendar.csv**](./templates/renewal-calendar.csv) | 12-month renewal tracker | Set reminders 60 days before renewals |
| [**renewal-tracker.py**](./scripts/renewal-tracker.py) | Automated renewal reminder script | Run monthly to get alerts |

### ❓ FAQ

| Document | What It Covers |
|----------|----------------|
| [**FAQ.md**](./FAQ.md) | Common questions about SaaS audits, consolidation, negotiation |

---

## Quick Start: 4-Step Process

### Step 1: Discover (Week 1)

**Build your SaaS inventory** - Find every tool your company pays for

**Sources**:
- Finance/accounting records (recurring charges)
- IT department (SSO logins, user provisioning)
- Department surveys (shadow IT tools)
- Credit card statements
- App store subscriptions

**Output**: Complete inventory with tool name, vendor, cost, users, renewal date

**Time**: 2-4 hours
**Guide**: [01-inventory.md](./guides/01-inventory.md)

---

### Step 2: Analyze (Week 2)

**Score each tool** - Identify waste and redundancy

**Analysis dimensions**:
1. **Usage** - How many people actually use this? (SSO login data)
2. **Value** - What business outcome does this enable?
3. **Overlap** - Do we have other tools that do the same thing?
4. **Cost per user** - Is this expensive relative to alternatives?
5. **Required vs nice-to-have** - Would the business break without this?

**Output**: Each tool scored as Keep / Consolidate / Negotiate / Cancel

**Time**: 2-3 hours
**Guide**: [02-usage-analysis.md](./guides/02-usage-analysis.md)

---

### Step 3: Optimize (Week 3)

**Take action** - Consolidate, negotiate, cancel

**Actions by category**:

**Cancel** (Score: 0-3/10):
- Unused tools (zero logins in 90 days)
- Duplicates after consolidation
- Shadow IT not aligned with company tools

**Negotiate** (Score: 6-8/10):
- Critical tools with upcoming renewals
- Tools you've used >2 years (ask for loyalty discount)
- Tools where you're paying list price

**Consolidate** (Score: 4-6/10):
- Multiple tools in same category
- Opportunities to use all-in-one platforms
- Features available in tools you already pay for

**Output**: $X,000/month in savings identified and executed

**Time**: 4-6 hours + ongoing negotiations
**Guides**: [03-consolidation.md](./guides/03-consolidation.md), [04-negotiation.md](./guides/04-negotiation.md)

---

### Step 4: Govern (Ongoing)

**Prevent future sprawl** - Set up approval process

**Governance framework**:
1. **Procurement approval** - All new SaaS requires VP/CFO sign-off
2. **Renewal review** - Quarterly check-in on utilization
3. **Deprovisioning** - Offboard process removes unused licenses
4. **Consolidation first** - Before buying new tool, check if existing tool can do it
5. **Annual audit** - Repeat this process every 12 months

**Output**: SaaS spend stays optimized long-term

**Time**: 1-2 hours setup, then 30 min/quarter maintenance
**Guides**: [05-governance.md](./guides/05-governance.md), [06-annual-review.md](./guides/06-annual-review.md)

---

## Common Tool Categories

Here are the most common categories where we see waste and consolidation opportunities:

### Productivity & Collaboration

**Common tools**: Google Workspace, Microsoft 365, Slack, Notion, Airtable, Asana, Monday, ClickUp, Trello

**Consolidation opportunities**:
- Notion can replace Asana/Trello/Confluence for many teams
- Google Workspace includes Sheets (can replace Airtable for simple use cases)
- Slack + Google Drive can replace many specialized collaboration tools

**Typical savings**: $500-2,000/month

---

### CRM & Sales

**Common tools**: HubSpot, Salesforce, Pipedrive, Zoho CRM, Freshsales, Intercom, Drift

**Consolidation opportunities**:
- Many teams pay for HubSpot CRM + Marketing + Sales when they only need 1-2 modules
- Live chat (Intercom/Drift) often included in CRM tools at lower cost
- See our [CRM Migration Guide](../crm-migration-guide/) for detailed comparison

**Typical savings**: $300-1,500/month

---

### Marketing & Email

**Common tools**: Mailchimp, HubSpot Marketing, SendGrid, Brevo (formerly Sendinblue), ConvertKit

**Consolidation opportunities**:
- Brevo offers generous free tier (300 emails/day) vs Mailchimp paid plans
- HubSpot Marketing can replace Mailchimp + landing page tools
- SendGrid more cost-effective for transactional email than Mailchimp

**Typical savings**: $200-800/month

---

### Project Management

**Common tools**: Asana, Monday, ClickUp, Jira, Trello, Basecamp

**Consolidation opportunities**:
- Most teams only need ONE project management tool
- Notion can replace project management for non-technical teams
- ClickUp offers more features at lower cost than Asana/Monday

**Typical savings**: $400-1,200/month (if paying for multiple tools)

---

### Design & Creative

**Common tools**: Adobe Creative Cloud, Figma, Canva, Sketch

**Consolidation opportunities**:
- Canva Pro ($13/user) replaces 80% of Adobe CC use cases for non-designers
- Figma free tier sufficient for many startups
- Stock photo subscriptions often unused (cancel and use free alternatives)

**Typical savings**: $300-1,500/month

---

### Finance & Accounting

**Common tools**: QuickBooks, Xero, Stripe, PayPal, Bill.com, Expensify

**Consolidation opportunities**:
- Stripe billing can replace separate invoicing tools
- Many accounting tools include expense management (don't need separate Expensify)
- Xero typically cheaper than QuickBooks for similar features

**Typical savings**: $100-500/month

---

## Savings Opportunities by Company Size

### 10-25 employees

**Typical SaaS spend**: $800-2,000/month
**Savings potential**: $240-800/month (30-40%)
**Low-hanging fruit**:
- Cancel unused tools (old trial accounts still billing)
- Downgrade overbuilt plans (Enterprise → Professional)
- Free alternatives (Mailchimp → Brevo, Asana → Notion)

---

### 25-50 employees

**Typical SaaS spend**: $2,000-4,000/month
**Savings potential**: $800-1,600/month (40-45%)
**Low-hanging fruit**:
- Consolidate project management (3 tools → 1 tool)
- Negotiate renewals (ask for 15-20% discount)
- All-in-one platforms (Zoho ONE, Google Workspace)

---

### 50-100 employees

**Typical SaaS spend**: $4,000-8,000/month
**Savings potential**: $1,600-3,500/month (40-50%)
**Low-hanging fruit**:
- Volume discounts (renegotiate all major tools)
- Remove unused licenses (employees who left)
- Strategic consolidation (replace 10-15 tools with Zoho ONE)

---

### 100+ employees

**Typical SaaS spend**: $8,000-25,000/month
**Savings potential**: $3,000-10,000/month (30-40%)
**Low-hanging fruit**:
- Enterprise agreements (better per-seat pricing)
- Vendor managed services (free migration help)
- Dedicated account management (custom pricing)

---

## Next Steps

1. **Read** [AUDIT-PROCESS.md](./AUDIT-PROCESS.md) to understand the full methodology (15 min)
2. **Download** [saas-inventory.csv](./templates/saas-inventory.csv) template
3. **Build inventory** following [01-inventory.md](./guides/01-inventory.md) (2-4 hours)
4. **Score tools** using [02-usage-analysis.md](./guides/02-usage-analysis.md) (2-3 hours)
5. **Check alternatives** in [ALTERNATIVES.md](./ALTERNATIVES.md) for consolidation ideas
6. **Negotiate renewals** using tactics from [NEGOTIATION.md](./NEGOTIATION.md)
7. **Set up governance** following [05-governance.md](./guides/05-governance.md)

**Total time**: 8-16 hours over 2-4 weeks
**Expected savings**: 30-50% of current SaaS spend
**Annual ROI**: 10-20x the time invested

---

## Related Guides

After optimizing your SaaS stack, consider these related resources:

- **[n8n SEA Guide](../n8n-sea-guide/)** - Replace Zapier with n8n (90-98% cheaper)
- **[CRM Migration Guide](../crm-migration-guide/)** - Migrate from HubSpot/Salesforce to save $200-500/month
- **[OpenClaw SEA Guide](../openclaw-sea-guide/)** - Self-hosted AI assistant ($5-25/month vs ChatGPT Teams $30/user)

---

## Contributing

This guide is maintained by [Pertama Partners](https://pertama.partners). For questions, corrections, or suggestions:

- Open an issue on GitHub
- Email: [Contact via website]

---

## License

MIT License - See [LICENSE](../LICENSE) for details.

---

**Last Updated**: February 6, 2026
**Version**: 1.0
