# AI Model Selection Guide
**Choose the right AI provider for your business - save time and money**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A practical guide for founders and business leaders to navigate the AI provider landscape (OpenAI, Anthropic, Google, DeepSeek, Mistral) and choose the right models for their specific needs.

---

## The Problem

You want to adopt AI for your business, but the landscape is overwhelming:

- 🤯 **Too many options**: OpenAI (GPT-4o, o-series), Anthropic (Claude), Google (Gemini), DeepSeek, Mistral, Perplexity...
- 💸 **Pricing confusion**: $0/month to $60/user/month, plus per-token API pricing that varies 100x between models
- 📊 **Capability overlap**: All providers claim to be "best" - but which is actually best for YOUR use case?
- 🔄 **Constant changes**: New models released monthly, pricing changes quarterly, features update weekly
- 🌏 **SEA considerations**: Not all providers available in Singapore/Malaysia, local payment methods vary
- 🔒 **Enterprise vs consumer**: What features justify $60/user vs $20/user? Do you even need enterprise?

**The founder's dilemma**: You see competitors using AI successfully, but you don't know which provider to choose, whether to use consumer apps or APIs, and how to avoid overspending on capabilities you don't need.

---

## The Solution: Strategic Model Selection Framework

This guide uses a **three-level approach** to separate stable strategy from frequently-changing execution details:

1. **STRATEGY** (guides/): How to think about AI models and assess your needs (updated rarely)
2. **TACTICS** (use-cases/): Best models for specific tasks like writing, coding, research (updated quarterly)
3. **EXECUTION** (providers/): Current pricing, specs, features per provider (updated monthly)

### 90-Day AI Provider Adoption Roadmap

#### Phase 1: Free Tier Testing (Week 1-2)
**Impact**: Understand capabilities without spending money

- ✅ **Sign up for free tiers** (1 hour)
  - ChatGPT Free (OpenAI)
  - Claude Free (Anthropic)
  - Gemini Free (Google)
  - **Result**: Test all major providers at zero cost

- ✅ **Run real-world tests** (3-5 hours)
  - Use same prompts across all providers
  - Test on actual work (emails, docs, code)
  - Measure quality differences
  - **Result**: Know which model works best for YOUR tasks

- ✅ **Assess needs** (30 min)
  - Complete needs assessment worksheet
  - Define top 3 use cases
  - Set monthly budget constraint
  - **Result**: Clear requirements documented

**Time**: 5-7 hours | **Cost**: $0 | **Output**: Shortlist of 2-3 providers

---

#### Phase 2: Paid Tier Evaluation (Week 3-4)
**Impact**: Get full capabilities, compare at production scale

- ✅ **Subscribe to top 2 providers** (15 min)
  - ChatGPT Plus ($20/month) OR Claude Pro ($20/month)
  - Perplexity Pro ($20/month) if research-heavy
  - **Result**: Full feature access for testing

- ✅ **Production testing** (2-3 weeks)
  - Use for daily work
  - Track time saved
  - Monitor costs (API usage if applicable)
  - Get team feedback
  - **Result**: Real-world ROI data

- ✅ **Cost-benefit analysis** (1 hour)
  - Calculate hours saved per month
  - Compare to subscription cost
  - Project 12-month value
  - **Result**: Clear ROI justification

**Time**: 3 weeks + 3 hours | **Cost**: $40-60 | **Output**: Final provider selection with ROI data

---

#### Phase 3: Team Rollout (Month 2-3)
**Impact**: Scale AI across organization

- ✅ **Procurement** (1-2 hours)
  - Purchase team seats
  - Negotiate volume discounts if 10+ users
  - Set up billing/admin
  - **Result**: Team accounts provisioned

- ✅ **Training & onboarding** (2-4 hours)
  - Create internal AI usage guide
  - Run training sessions (prompt engineering basics)
  - Set usage policies (data classification)
  - **Result**: Team knows how to use AI effectively and safely

- ✅ **Monitor & optimize** (ongoing)
  - Track usage patterns
  - Identify power users
  - Optimize costs (switch models if needed)
  - **Result**: Maximized ROI

**Time**: 10-15 hours | **Cost**: $60-200/month (depends on team size) | **Output**: AI-enabled team

---

## Quick Decision Tree

Use this decision tree to get a fast recommendation. For detailed comparisons, see the full documentation.

```
START: What's your primary use case?
│
├─ "Just exploring AI - not sure yet"
│  └─> Start with: ChatGPT Free + Claude Free (rotate both)
│     Then read: guides/01-understanding-models.md
│
├─ "Writing content (blogs, social media, emails)"
│  ├─ Budget < $20/month?
│  │  └─> Claude Free (best free writing model)
│  ├─ Budget $20/month?
│  │  └─> Claude Pro (best for writing quality)
│  └─ Need SEO optimization?
│     └─> See: use-cases/01-content-creation.md (may need Jasper)
│
├─ "Research with citations (market research, competitive analysis)"
│  └─> Perplexity Pro ($20/month)
│     Alternative: ChatGPT Plus (web search included)
│
├─ "Code generation (development, debugging)"
│  ├─ Budget sensitive?
│  │  └─> DeepSeek ($3-8/month API) - see: providers/04-deepseek.md
│  ├─ Need best quality?
│  │  └─> Claude Pro ($20/month) - excellent at code
│  └─> Also consider: ChatGPT Plus (good all-rounder)
│
├─ "Data analysis (spreadsheets, reports, insights)"
│  └─> ChatGPT Plus ($20/month)
│     Reason: Advanced Data Analysis (code interpreter)
│
├─ "Multiple use cases (all-around productivity)"
│  ├─ Budget $20/month?
│  │  └─> ChatGPT Plus (best all-around: search, images, data, code)
│  ├─ Budget $40/month?
│  │  └─> ChatGPT Plus + Claude Pro (use each for its strength)
│  └─ Google Workspace heavy user?
│     └─> Gemini Advanced ($20/month) - integrates with Gmail/Docs
│
├─ "Enterprise needs (SSO, admin controls, compliance)"
│  ├─ Microsoft 365 user?
│  │  └─> Microsoft Copilot ($30/user/month)
│  ├─ Need SOC 2 / data residency?
│  │  └─> See: guides/05-enterprise-considerations.md (in future)
│  └─> Consider: ChatGPT Enterprise ($60/user) or Claude for Work
│
└─ "Want to self-host / open source"
   └─> See: providers/08-open-source.md (Llama, Qwen, hosting)
```

---

## Quick Recommendations by Budget

### Budget: $0/month
- **ChatGPT Free** + **Claude Free**: Rotate between both, use each for what it's best at
- **Gemini Free**: If you're a Google Workspace user
- **Limitation**: Message limits, no advanced features

### Budget: $20/month (Single User)
- **Best All-Around**: ChatGPT Plus (web search, images, data analysis)
- **Best for Writing**: Claude Pro (200K context, excellent writing)
- **Best for Research**: Perplexity Pro (citations, up-to-date)

### Budget: $40/month (Single User)
- **Recommended Combo**: ChatGPT Plus + Claude Pro
- **Use ChatGPT for**: Research, data analysis, image generation
- **Use Claude for**: Long document editing, complex writing, code

### Budget: $20/user/month (Team of 3-10)
- **Start with**: ChatGPT Team ($25/user/month, billed annually)
- **Why**: Admin controls, higher limits, better support
- **Alternative**: Claude for Work ($30/user/month) if writing-focused

### Budget: $60/user/month (Enterprise, 50+ users)
- **Options**: ChatGPT Enterprise, Claude for Enterprise, Microsoft Copilot
- **See**: guides/05-enterprise-considerations.md (future)

---

## Documentation Structure

### Strategy (Stable - Read First)
Foundational knowledge that rarely changes:

| Guide | Description | Time | When to Read |
|-------|-------------|------|--------------|
| [01-understanding-models.md](guides/01-understanding-models.md) | How AI models work (non-technical) | 15 min | Start here if new to AI |
| [02-needs-assessment.md](guides/02-needs-assessment.md) | Self-assessment framework | 30 min | Before choosing provider |
| [03-build-vs-buy.md](guides/03-build-vs-buy.md) | Consumer apps vs API vs enterprise | 20 min | If considering API usage |
| [04-cost-optimization.md](guides/04-cost-optimization.md) | Manage AI spend | 25 min | After 2-3 months of usage |

### Execution (Updated Monthly - Check Regularly)
Current provider details (pricing, features, models):

| Provider Guide | Best For | Price Range | Last Updated |
|----------------|----------|-------------|--------------|
| [00-comparison.md](providers/00-comparison.md) | **Master comparison table** | All | 2026-02 |
| [01-openai.md](providers/01-openai.md) | All-around, research, data | $0-60/user | 2026-02 |
| [02-anthropic.md](providers/02-anthropic.md) | Writing, long documents | $0-30/user | 2026-02 |
| [03-google.md](providers/03-google.md) | Google Workspace integration | $0-20/user | 2026-02 |
| [04-deepseek.md](providers/04-deepseek.md) | Budget code generation | $3-8 API | 2026-02 |
| [05-others.md](providers/05-others.md) | Specialized needs | Varies | 2026-02 |

### Tactics (Updated Quarterly - By Use Case)
Which model for which task:

| Use Case | Best Model (Current) | Time | For Who |
|----------|----------------------|------|---------|
| [01-content-creation.md](use-cases/01-content-creation.md) | Claude Pro, ChatGPT Plus | 20 min | Marketers, writers |
| [02-code-generation.md](use-cases/02-code-generation.md) | Claude Pro, DeepSeek | 20 min | Developers |
| [03-research-analysis.md](use-cases/03-research-analysis.md) | Perplexity Pro, ChatGPT | 20 min | Analysts, researchers |

### Templates
Reusable worksheets:

| Template | Description | Format |
|----------|-------------|--------|
| [model-evaluation-checklist.md](templates/model-evaluation-checklist.md) | Evaluate and compare providers | Fill-in-the-blank |

---

## Who This Is For

✅ **This guide is for you if you**:
- Are a founder/CEO/business leader evaluating AI providers
- Want to choose the right model without technical expertise
- Need to justify AI spending to stakeholders
- Want to avoid overpaying for features you don't need
- Are in Southeast Asia (Singapore, Malaysia, Indonesia, Thailand)
- Have a team of 1-50 people considering AI adoption

✅ **You'll get value from this if**:
- You're spending 10+ hours/week on writing, research, or data analysis
- Your team could save 20%+ time with AI assistance
- You're confused by GPT vs Claude vs Gemini comparisons
- You want to start with free tiers and upgrade strategically

---

## Who This Is NOT For

❌ **This guide is NOT for you if you**:
- Need to build custom AI applications (this focuses on consumer/enterprise AI tools)
- Are a machine learning engineer (this is for non-technical business leaders)
- Already have deep AI expertise (this is beginner-to-intermediate)
- Work at a 1,000+ employee company (enterprise needs are more complex)

❌ **You probably don't need this if**:
- You're happy with your current AI provider (no need to switch)
- You have dedicated AI/ML team (they should handle provider selection)
- You're in heavily regulated industry (financial services, healthcare) - need specialized compliance advice

---

## Expected Results by Company Size

### Solo Founder / 1-3 Person Team
- **Investment**: $0-40/month, 10 hours setup
- **Savings**: 15-20 hours/month (writing, research, data analysis)
- **ROI**: Break-even in Week 1, $3,000-5,000/year value
- **Best Starting Point**: ChatGPT Plus ($20/month)

### Small Team (4-10 People)
- **Investment**: $100-300/month, 20 hours setup
- **Savings**: 60-100 hours/month across team
- **ROI**: Break-even in Month 1, $15,000-25,000/year value
- **Best Starting Point**: ChatGPT Team ($25/user/month)

### Growing Company (11-50 People)
- **Investment**: $500-1,500/month, 40 hours setup + training
- **Savings**: 200-400 hours/month across team
- **ROI**: Break-even in Month 2, $50,000-100,000/year value
- **Best Starting Point**: ChatGPT Team or Claude for Work

---

## Common Questions

### Q: Which is better - ChatGPT or Claude?
**A**: Depends on use case. ChatGPT is best all-around (web search, images, data analysis). Claude is best for writing quality and long documents. For most businesses starting out, ChatGPT Plus ($20/month) is the safer first choice. If you can afford $40/month, get both and use each for its strength.

### Q: Should I use free tiers or paid plans?
**A**: Start with free tiers (ChatGPT Free, Claude Free) to test for 1-2 weeks. If you use AI daily and it saves >1 hour/week, upgrade to paid ($20/month). ROI is typically positive within days for knowledge workers.

### Q: What about Google Gemini or Microsoft Copilot?
**A**: Choose Gemini if you're a heavy Google Workspace user (Gmail, Docs, Sheets integration). Choose Microsoft Copilot if you're a Microsoft 365 enterprise customer. Otherwise, ChatGPT or Claude are better standalone options.

### Q: Is API usage cheaper than consumer subscriptions?
**A**: Depends on volume. For <100,000 tokens/month (~75,000 words), consumer subscriptions ($20/month) are usually cheaper and simpler. For higher volumes or specialized models, API can be more cost-effective. See [guides/03-build-vs-buy.md](guides/03-build-vs-buy.md) for detailed comparison.

### Q: How often do prices change?
**A**: Pricing typically changes 1-4 times per year. Features and models update monthly. We track all changes in [CHANGELOG.md](CHANGELOG.md) and update provider files monthly.

### Q: Are these providers available in Southeast Asia?
**A**: Yes, with some caveats. Anthropic (Claude), Google (Gemini), and most major providers work across Singapore, Malaysia, Indonesia, Thailand, Vietnam, and Philippines. OpenAI (ChatGPT) has expanded to most SEA markets but availability and payment methods can vary by country — check OpenAI's supported countries page for the latest. See individual provider files for SEA-specific details including accepted payment methods and data residency.

### Q: What if I choose wrong and want to switch?
**A**: Consumer subscriptions are month-to-month (no long-term contracts). You can cancel anytime. Your conversation history is exportable from most providers. Switching providers is low-risk and takes <1 hour. See [guides/04-model-migration.md](guides/04-model-migration.md) (future).

### Q: Do I need "Enterprise" plans?
**A**: Only if you need SSO, admin controls, or compliance certifications (SOC 2, HIPAA). For teams <20 people, consumer/Team plans are usually sufficient. Enterprise makes sense at 50+ users or for regulated industries.

---

## Next Steps

Choose your path based on where you are:

### Path A: Completely New to AI
1. **Read**: [guides/01-understanding-models.md](guides/01-understanding-models.md) (15 min)
2. **Sign up**: ChatGPT Free + Claude Free
3. **Test**: Use for 1 week on real work
4. **Decide**: If valuable, upgrade to paid tier ($20/month)

### Path B: Tried AI, Want to Choose Best Provider
1. **Complete**: [guides/02-needs-assessment.md](guides/02-needs-assessment.md) (30 min)
2. **Review**: [providers/00-comparison.md](providers/00-comparison.md) (10 min)
3. **Follow**: Decision tree above to get recommendation
4. **Test**: Free trial of top 2 providers (1-2 weeks)
5. **Subscribe**: Winning provider

### Path C: Already Using AI, Want to Optimize Costs
1. **Read**: [guides/04-cost-optimization.md](guides/04-cost-optimization.md) (25 min)
2. **Audit**: Current spending and usage patterns
3. **Compare**: Alternative providers in [providers/00-comparison.md](providers/00-comparison.md)
4. **Test**: Cheaper alternatives (e.g., DeepSeek vs GPT-4 for code)
5. **Switch**: If ROI justifies it

### Path D: Rolling Out to Team
1. **Pilot**: Test with 2-3 users for 2-4 weeks
2. **Document**: Internal use cases and ROI
3. **Train**: Team on prompt engineering basics
4. **Set policy**: Usage guidelines (see [templates/ai-usage-policy.md](templates/ai-usage-policy.md) - future)
5. **Roll out**: Provision team accounts
6. **Monitor**: Track usage and optimize

---

## Related Guides

**From Pertama Partners Resources**:
- [AI Implementation Playbook](../ai-implementation-playbook/) - How to adopt AI across 10 business functions
- [AI Tooling Security Guide](../ai-tooling-security-guide/) - How to safely use AI tools (skills, plugins, extensions)
- [OpenClaw SEA Guide](../openclaw-sea-guide/) - Claude Code skills installation guide for Southeast Asia

**External Resources**:
- [Artificial Analysis](https://artificialanalysis.ai/) - Independent AI model benchmarks
- [LLM Pricing](https://llmpricing.co/) - Real-time API pricing comparison

---

## Contributing

Found outdated pricing or new model releases? Please contribute:
1. Create an issue or pull request on [GitHub](https://github.com/michaelhauge/pertama-partners-resources)
2. Include: Provider name, what changed, source link, date
3. We review and update monthly

---

## Changelog

Track all provider updates in [CHANGELOG.md](CHANGELOG.md).

**Last Updated**: 2026-02-07
**Next Review**: 2026-03-07

---

## License

MIT License - See [LICENSE](../LICENSE) for details.

**Maintained by**: [Pertama Partners](https://pertamapartners.com)
**Repository**: https://github.com/michaelhauge/pertama-partners-resources
