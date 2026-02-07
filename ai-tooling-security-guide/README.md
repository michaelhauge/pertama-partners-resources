# AI Tooling Security Guide
**Protect Your Business While Adopting AI Tools**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A practical guide for CEOs and business leaders who want to safely use AI tools (Claude Code skills, MCP servers, ChatGPT plugins, browser extensions) without exposing their companies to malware, data theft, or supply chain attacks.

---

## The Problem

You want to use powerful AI tools from the community, but you're worried about security:

- 📉 **60% of browser extensions** request excessive permissions they don't actually need
- 🚨 **Malicious extensions** are removed from Chrome Web Store every week, often after gaining 100,000+ users
- 💰 **Data theft costs** average $4.45M per incident (IBM 2025)
- 🔓 **83% of organizations** experienced a supply chain attack in the past year
- 🎯 **AI tools are new attack vectors**: Skills, plugins, and extensions can access your files, API keys, and sensitive data

**The founder's dilemma**: You see colleagues downloading Claude Code skills from GitHub, installing MCP servers, and using ChatGPT plugins - but you don't know how to tell if they're safe. One bad install could expose your entire company.

---

## The Solution: 90-Day Security Roadmap

### Quick Wins (Week 1-2): Immediate Risk Reduction
**Impact**: Stop active threats, establish baseline security

- ✅ **Run Security Assessment** (30 min)
  - Identify what AI tools are currently installed
  - Score your current risk level
  - Get immediate action items
  - **Result**: Know exactly where you stand

- ✅ **Audit Existing Tools** (1 hour)
  - Review every AI tool, extension, plugin currently in use
  - Remove anything from unknown sources
  - Disable anything not actively needed
  - **Result**: Surface area reduced by 40-60%

- ✅ **Install Security Scripts** (30 min)
  - Set up skill-scanner.py to check skills before installing
  - Run permissions-audit.sh on current setup
  - Bookmark trusted sources (TOOLS.md)
  - **Result**: Automated threat detection in place

**Time**: 2 hours | **Cost**: Free | **Risk Reduction**: 50-70%

---

### Phase 2 (Month 1): Establish Vetting Process
**Impact**: Prevent future threats before they enter

- ✅ **Create Vetting Workflow** (2 hours)
  - Define approval process for new AI tools
  - Train team on skill vetting checklist
  - Set up review schedule (quarterly audits)
  - **Result**: No unapproved tools get installed

- ✅ **Implement Data Protection** (3 hours)
  - Map what data AI tools can access
  - Implement least-privilege access
  - Move sensitive files out of AI tool reach
  - Create separate accounts for AI experiments
  - **Result**: Sensitive data isolated from AI tools

- ✅ **Set Usage Policies** (2 hours)
  - Deploy AI Acceptable Use Policy
  - Communicate approved tools list
  - Set up incident reporting process
  - **Result**: Team knows the rules

**Time**: 7 hours | **Cost**: Free-$500 (if hiring consultant for policy review) | **Risk Reduction**: 30-40% additional

---

### Phase 3 (Month 2-3): Vendor Evaluation & Enterprise Hardening
**Impact**: Enterprise-grade AI tool security

- ✅ **Evaluate AI Vendors** (4 hours)
  - Review SOC 2 / ISO 27001 certifications
  - Assess data retention and training policies
  - Negotiate enterprise agreements
  - Conduct vendor security questionnaires
  - **Result**: Only certified vendors approved

- ✅ **Sandbox High-Risk Tools** (4 hours)
  - Set up Docker isolation for MCP servers
  - Create separate environment for experimental skills
  - Implement browser profiles for extension testing
  - **Result**: Blast radius contained

- ✅ **Incident Response Prep** (2 hours)
  - Document incident response plan for AI threats
  - Designate response team
  - Set up monitoring/alerting
  - Run tabletop exercise
  - **Result**: Ready to respond if breach occurs

**Time**: 10 hours | **Cost**: $1,000-3,000 (Docker, monitoring tools, consultant) | **Risk Reduction**: 20-30% additional

---

## 📊 Expected Total Results

| Metric | Before | After 90 Days | Improvement |
|--------|---------|---------------|-------------|
| **Unapproved tools installed** | 8-15 | 0 | 100% reduction |
| **Tools with excessive permissions** | 5-10 | 0-1 | 90% reduction |
| **Data exposure risk** | High | Low | 70% reduction |
| **Time to vet new tool** | Unknown/skipped | 15 min | Process established |
| **Incident response time** | Days | Hours | 80% faster |
| **Compliance posture** | Failing | Passing | ✅ |

**Total Investment**: $1,000-3,500 + 19 hours over 90 days
**Potential Breach Cost Avoided**: $500k-4.5M (average data breach)
**ROI**: 14,000% - 450,000%

---

## 👥 Who This Is For

This guide is designed for:

- ✅ **CEOs and founders** who want to use AI tools but don't have security expertise
- ✅ **Small-to-mid-size businesses** (5-200 employees) without dedicated security teams
- ✅ **Leaders in SEA** navigating PDPA compliance while adopting AI
- ✅ **Teams using Claude Code, ChatGPT, or other AI platforms** and downloading community tools
- ✅ **Companies concerned about supply chain attacks** through AI tool dependencies
- ✅ **Anyone who's heard "just download this skill"** and wondered if it's safe

---

## ❌ Who This Is NOT For

This guide is NOT designed for:

- ❌ **Large enterprises with security teams** - You need enterprise security frameworks (NIST, CIS)
- ❌ **Security engineers** - You already know this; you need penetration testing, not checklists
- ❌ **Companies that won't use any AI tools** - If you're blocking all AI, you don't need vetting processes
- ❌ **Developers who can code review** - If you can audit source code yourself, you're beyond this guide

---

## 🗺️ Quick Decision Tree

Not sure where to start? Follow this tree:

```
START: What are you trying to do?
│
├─ "I found a Claude Code skill on GitHub"
│  └─> Go to: guides/02-skill-vetting.md (15 min checklist)
│
├─ "Someone sent me an MCP server to install"
│  └─> Go to: guides/03-mcp-servers.md (How to evaluate)
│
├─ "I want to install a ChatGPT plugin or custom GPT"
│  └─> Go to: guides/05-chatgpt-plugins.md (Plugin security)
│
├─ "My team is installing AI browser extensions"
│  └─> Go to: guides/04-browser-extensions.md (Extension audit)
│
├─ "I don't know what AI tools we even have installed"
│  └─> Go to: guides/01-assessment.md (Security assessment)
│
├─ "I want to know what AI vendors to trust"
│  └─> Go to: guides/07-vendor-evaluation.md (Vendor checklist)
│
├─ "I think we might have installed something malicious"
│  └─> Go to: guides/08-incident-response.md (IMMEDIATE ACTION)
│
└─ "I just want to learn about the risks"
   └─> Read: THREATS.md (Threat landscape explained)
```

---

## 📁 Documentation Structure

### Core Reference Documents

| Document | Description | When to Use |
|----------|-------------|-------------|
| **[TOOLS.md](TOOLS.md)** | Trusted sources and safe AI tools | Finding verified tools to use |
| **[THREATS.md](THREATS.md)** | Threat landscape for non-technical readers | Understanding what can go wrong |
| **[FAQ.md](FAQ.md)** | Common security questions answered | Quick answers |

---

### 🛠️ Implementation Guides

| Guide | Description | Time | Priority |
|-------|-------------|------|----------|
| **[01-assessment.md](guides/01-assessment.md)** | AI tool security self-assessment (100-point scorecard) | 30 min | 🔴 Start Here |
| **[02-skill-vetting.md](guides/02-skill-vetting.md)** | How to vet Claude Code skills before installing | 15 min | 🔴 High |
| **[03-mcp-servers.md](guides/03-mcp-servers.md)** | MCP server security evaluation process | 1 hour | 🔴 High |
| **[04-browser-extensions.md](guides/04-browser-extensions.md)** | AI browser extension security audit | 30 min | 🟡 Medium |
| **[05-chatgpt-plugins.md](guides/05-chatgpt-plugins.md)** | ChatGPT/custom GPT security checklist | 30 min | 🟡 Medium |
| **[06-data-protection.md](guides/06-data-protection.md)** | What data AI tools can access and how to protect it | 45 min | 🔴 High |
| **[07-vendor-evaluation.md](guides/07-vendor-evaluation.md)** | Evaluating AI vendors and providers | 1 hour | 🟡 Medium |
| **[08-incident-response.md](guides/08-incident-response.md)** | What to do if something goes wrong | 15 min read | 🔴 High |

---

### 📄 Ready-to-Use Templates

| Template | Description | Use Case |
|----------|-------------|----------|
| **[skill-review-checklist.md](templates/skill-review-checklist.md)** | Checklist for reviewing Claude Code skills | Before installing any skill from community |
| **[vendor-ai-questionnaire.md](templates/vendor-ai-questionnaire.md)** | Questions to ask AI vendors | Evaluating AI SaaS providers |
| **[ai-acceptable-use-policy.md](templates/ai-acceptable-use-policy.md)** | Company policy for AI tool usage | Rolling out AI tools to team |
| **[incident-report-ai.md](templates/incident-report-ai.md)** | Template for AI security incidents | After detecting malicious tool |

---

### 🤖 Security Scripts

| Script | Description | Usage |
|--------|-------------|-------|
| **[skill-scanner.py](scripts/skill-scanner.py)** | Scan Claude Code skills for security red flags | `python3 skill-scanner.py ~/.claude/skills/skill-name/` |
| **[permissions-audit.sh](scripts/permissions-audit.sh)** | Audit what AI tools can access on your system | `./permissions-audit.sh` |

---

## 💰 Cost Breakdown by Phase

### Phase 1: Quick Wins (Week 1-2)
| Item | Cost | Note |
|------|------|------|
| Assessment (time only) | Free | 30 min of your time |
| Security scripts | Free | Open source |
| Tool audit (time only) | Free | 1 hour of your time |
| **Phase 1 Total** | **$0** | Time investment only |

### Phase 2: Vetting Process (Month 1)
| Item | Cost | Note |
|------|------|------|
| Policy templates | Free | Provided in this guide |
| Training (time only) | Free | 2 hours team meeting |
| Optional: Policy review consultant | $500 | If you want expert review |
| **Phase 2 Total** | **$0-500** | Optional consultant |

### Phase 3: Enterprise Hardening (Month 2-3)
| Item | Cost | Note |
|------|------|------|
| Docker Desktop (if sandboxing MCP) | $9/mo | Per user needing it |
| Optional: Security monitoring tool | $50-100/mo | For larger teams |
| Optional: Tabletop exercise consultant | $1,000 | One-time |
| **Phase 3 Total** | **$1,000-3,000** | For ~10-person team |

**Total 90-Day Investment**: $1,000-3,500 + 19 hours

---

## ❓ Common Questions

### "Is OpenClaw safe? Can I use those skills?"

**Short answer**: Probably, but verify yourself. OpenClaw is a community project with good vetting, but it's not immune to supply chain attacks.

**What to do**:
1. Use [skill-scanner.py](scripts/skill-scanner.py) on any OpenClaw skill before installing
2. Follow the [skill vetting checklist](guides/02-skill-vetting.md)
3. Prefer skills from verified authors with many GitHub stars

---

### "Can AI tools steal my API keys?"

**Short answer**: Yes, absolutely. Claude Code skills, MCP servers, and extensions can read files like `.env` where API keys are stored.

**What to do**:
1. Read [Data Protection Guide](guides/06-data-protection.md)
2. Use separate API keys for experimental tools (revoke if compromised)
3. Never store production API keys on machines running untrusted AI tools
4. Use environment variable isolation

---

### "What's the worst that can happen?"

**Short answer**: A malicious AI tool could:
- Steal all files on your computer and send them to an attacker
- Read your passwords, API keys, and credentials
- Install persistent backdoors that survive reboots
- Use your computer for crypto mining or botnet attacks
- Delete files or encrypt them for ransom

**Reality**: Most community tools are safe. But the risk is real, and the impact can be catastrophic. This guide helps you tell the difference.

---

### "Should I just ban all AI tools at my company?"

**Short answer**: No, that's not realistic in 2026. Your team will use AI tools anyway (shadow IT). Better to provide safe options.

**What to do**:
1. Create an approved tools list (see [TOOLS.md](TOOLS.md))
2. Set up a vetting process for new tools (see [skill vetting](guides/02-skill-vetting.md))
3. Implement an [AI acceptable use policy](templates/ai-acceptable-use-policy.md)
4. Make it easy to request new tools (fast approval for low-risk)

---

### "I'm not technical. Can I really evaluate these tools?"

**Short answer**: Yes. This guide is written for non-technical leaders. You don't need to code to use the checklists and scripts.

**What's provided**:
- ✅ Visual examples of what "suspicious" looks like
- ✅ Fill-in-the-blank checklists
- ✅ Scripts that do the technical work for you
- ✅ Clear go/no-go decision frameworks
- ✅ When to escalate to an expert

---

### "How often should I review AI tools?"

**Short answer**:
- **Quarterly audits** of all installed tools (remove unused, check for updates)
- **Before installing** any new tool (use vetting checklist)
- **Immediately** if you hear about a security incident with a tool you use

---

## 🎯 Next Steps

Choose your path:

### Path A: "I'm brand new to this"
1. Read [THREATS.md](THREATS.md) (15 min) to understand the risks
2. Run [01-assessment.md](guides/01-assessment.md) (30 min) to score your current security
3. Follow the recommendations from your assessment

### Path B: "I have a specific tool I want to install"
1. Is it a Claude Code skill? → [02-skill-vetting.md](guides/02-skill-vetting.md)
2. Is it an MCP server? → [03-mcp-servers.md](guides/03-mcp-servers.md)
3. Is it a browser extension? → [04-browser-extensions.md](guides/04-browser-extensions.md)
4. Is it a ChatGPT plugin? → [05-chatgpt-plugins.md](guides/05-chatgpt-plugins.md)

### Path C: "I want to set company-wide policies"
1. Review [TOOLS.md](TOOLS.md) for trusted sources
2. Customize [ai-acceptable-use-policy.md](templates/ai-acceptable-use-policy.md)
3. Train team on [skill vetting](guides/02-skill-vetting.md)
4. Set up quarterly reviews

### Path D: "Something went wrong / I'm worried we're compromised"
1. **IMMEDIATELY** go to [08-incident-response.md](guides/08-incident-response.md)
2. Follow containment steps
3. Contact security expert if needed

---

## 🔗 Related Guides

From **Pertama Partners Resources**:
- [SMB Cybersecurity Guide](../smb-cybersecurity-guide/) - General cybersecurity for small businesses
- [Remote Team Operations Guide](../remote-team-operations-guide/) - Managing remote teams securely

---

## 🤝 Contributing

Found an issue or have a suggestion? Please open an issue or submit a pull request on GitHub.

This guide is maintained by Pertama Partners and community contributors.

---

## 📜 License

MIT License - Free to use, modify, and distribute.

---

**Last Updated**: February 2026
**Version**: 1.0.0
**Maintained by**: Pertama Partners

---

**⚠️ Disclaimer**: This guide provides general security guidance but is not a substitute for professional security consultation. Every organization's risk tolerance and threat model is different. Consult with cybersecurity professionals for your specific needs.
