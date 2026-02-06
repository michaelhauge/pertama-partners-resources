# n8n Workflow Automation Guide for Southeast Asia

**A comprehensive guide for business leaders in Malaysia and Singapore**

---

## What is n8n?

n8n is a **powerful workflow automation platform** that helps businesses automate repetitive tasks and connect different applications without writing code. Think of it as a cheaper, more flexible alternative to Zapier.

### What Can It Do?

- **Lead Capture**: "When someone fills the website form, add them to CRM and send WhatsApp notification"
- **Invoice Processing**: "Extract data from email attachments and add to accounting software"
- **Customer Support**: "Route WhatsApp messages to the right team member based on keywords"
- **Report Generation**: "Every Monday, pull last week's data and email formatted report"
- **Expense Tracking**: "When I upload receipt photo, extract details and add to spreadsheet"
- **Appointment Reminders**: "Send WhatsApp reminder 24 hours before calendar appointments"

**Key Advantage**: n8n charges per workflow execution, not per step. A 10-step workflow counts as 1 execution on n8n but 10 tasks on Zapier—making n8n **90-98% cheaper** for complex automations.

---

## Why This Guide?

Many business leaders in Southeast Asia have heard about workflow automation but are hesitant because of:

- **Cost concerns**: Zapier is $30-75/month for basic usage
- **Technical complexity**: "Do I need to know Docker and databases?"
- **Security concerns**: "Where does my data go?"
- **Lack of clear instructions**: Want step-by-step guidance for SEA region

**This guide solves all of these problems.**

---

## Quick Start

### Total Monthly Cost: $0-15

Yes, you can run powerful workflow automation for free (self-hosted) or less than a lunch meeting.

| Component | Cost |
|-----------|------|
| n8n Software | **FREE** (open source) |
| Hosting | $0-6/month (or $24 for managed) |
| Database | Included |
| **Total** | **$0-30/month** |

**Compare to Zapier**: $30-75/month for basic plans

### Installation Options

1. **Local Mac** (Easiest, Free) - [Guide](guides/03-local-mac.md)
2. **Oracle Cloud Free** (Advanced, $0 forever) - [Guide](guides/04-oracle-cloud-free.md)
3. **Contabo VPS** (Best Value, ~$5.50/month) - [Guide](guides/06-contabo-vps.md)
4. **DigitalOcean** (Easiest VPS, $24/month) - [Guide](guides/05-digitalocean.md)

---

## Step-by-Step Path

### For Complete Beginners (Recommended)

1. **[Prerequisites](guides/01-prerequisites.md)** - Install Docker (15 minutes)
2. **[Choose Hosting](guides/02-choosing-hosting.md)** - Decide: local or VPS (5 minutes)
3. **[Install on Mac](guides/03-local-mac.md)** - Run n8n locally (10 minutes)
4. **[First Workflow](guides/07-first-workflow.md)** - Build your first automation (30 minutes)

**Total Time: ~60 minutes**

### For Cost-Conscious Users

1. **[Prerequisites](guides/01-prerequisites.md)** (15 minutes)
2. **[Oracle Cloud Free](guides/04-oracle-cloud-free.md)** - $0 hosting forever
3. **[First Workflow](guides/07-first-workflow.md)** - Start automating

**Total Cost: $0/month**

### For Privacy-Focused Users

1. **[Prerequisites](guides/01-prerequisites.md)** (15 minutes)
2. **[Install on Mac](guides/03-local-mac.md)** - Keep everything local
3. **[First Workflow](guides/07-first-workflow.md)** - Build automations

**Your data never leaves your machine**

### For "Just Make It Work" Users

1. **[n8n Cloud Sign Up](https://n8n.io/)** (5 minutes)
2. **[First Workflow](guides/07-first-workflow.md)** - Start building

**Cost**: €24/month (~$26), fully managed

---

## Is It Safe?

**Short answer: Yes, especially when self-hosted.**

n8n is fair-code software trusted by thousands of businesses worldwide including Fortune 500 companies.

### Common Security Concerns

| Fear | Reality |
|------|---------|
| "My data will be stolen" | Self-hosted = data stays on YOUR server |
| "Credentials will leak" | AES-256 encryption, OAuth support |
| "Integration risks" | You control which apps connect |
| "PDPA compliance" | Self-hosted in Singapore = full control |

**Read our complete [Security Guide](SECURITY.md) for details.**

---

## Cost Comparison: n8n vs Zapier

### Real-World Example

**Scenario**: Lead capture workflow with 10 steps, running 1,000 times/month

| Platform | Billing Method | Cost |
|----------|---------------|------|
| **Zapier Professional** | 10 steps × 1,000 executions = 10,000 tasks | **$75/month** |
| **n8n Self-Hosted** | 1,000 executions + $5.50 VPS | **$5.50/month** |
| **Savings** | | **$834/year** |

**Why?** Zapier charges per step, n8n charges per execution (no matter how many steps).

**See full [Pricing Breakdown](PRICING.md)**

---

## Documentation

### Core Guides

- **[Security](SECURITY.md)** - Addressing all security concerns
- **[Pricing](PRICING.md)** - Complete cost breakdown vs Zapier
- **[Use Cases](USE-CASES.md)** - 10 real examples for SEA businesses
- **[FAQ](FAQ.md)** - Common questions answered

### Installation Guides

1. **[Prerequisites](guides/01-prerequisites.md)** - Docker installation
2. **[Choosing Hosting](guides/02-choosing-hosting.md)** - Self-hosted vs cloud decision
3. **[Local Mac Installation](guides/03-local-mac.md)** - Run on your Mac
4. **[Oracle Cloud Free](guides/04-oracle-cloud-free.md)** - Free VPS hosting
5. **[DigitalOcean](guides/05-digitalocean.md)** - Easiest VPS option
6. **[Contabo VPS](guides/06-contabo-vps.md)** - Best value VPS
7. **[First Workflow](guides/07-first-workflow.md)** - Build your first automation
8. **[WhatsApp Integration](guides/08-whatsapp-integration.md)** - Connect WhatsApp Business
9. **[Telegram Integration](guides/09-telegram-integration.md)** - Connect Telegram

### Automation Tools

- **[Mac One-Click Installer](scripts/install-mac.sh)** - Automatic Docker + n8n setup
- **[Ubuntu Installer](scripts/install-ubuntu.sh)** - For VPS deployment
- **[Health Check](scripts/health-check.sh)** - Verify installation
- **[Cost Calculator](scripts/cost-calculator.sh)** - n8n vs Zapier comparison

---

## Popular Use Cases for SEA Businesses

### 1. E-commerce Order Automation
Shopee/Lazada order → Update inventory → Send to supplier → WhatsApp notification

### 2. Lead Management
Website form → Validate → Add to CRM → Assign sales rep → WhatsApp alert

### 3. Invoice Processing
Email PDF invoice → Extract data → Add to accounting → Update cash flow tracker

### 4. Customer Support
WhatsApp inquiry → Categorize → Route to team → Create ticket

### 5. Social Media Management
Google Sheet schedule → Post to multiple platforms → Track engagement

**See all [10 Use Cases](USE-CASES.md) with step-by-step workflows**

---

## ROI Example

**Small business running 5 workflows, 2,000 executions/month**

| Solution | Monthly Cost | Annual Cost |
|----------|-------------|-------------|
| Zapier (assuming 5 steps/workflow = 10,000 tasks) | $75 | $900 |
| n8n Self-Hosted (Contabo VPS) | $5.50 | $66 |
| **Annual Savings** | | **$834** |

Plus: Unlimited workflows, unlimited users, complete control over your data.

---

## Support & Community

This is a **self-service guide** created by [Pertama Partners](https://pertama.partners) as a free resource for the Southeast Asian business community.

### Getting Help

- **n8n Official Docs**: https://docs.n8n.io
- **n8n Community**: https://community.n8n.io
- **n8n GitHub**: https://github.com/n8n-io/n8n

### Contributing

Found an error or have a suggestion? Submit a pull request or open an issue on this repo.

---

## License

This guide is provided under the MIT License. n8n itself is licensed under the Sustainable Use License (fair-code).

---

## Quick Links

- [Official n8n Website](https://n8n.io)
- [n8n Documentation](https://docs.n8n.io)
- [n8n vs Zapier Comparison](https://n8n.io/vs/zapier/)

---

**Ready to save $500-1,000/year on automation? Head to [Prerequisites](guides/01-prerequisites.md) →**
