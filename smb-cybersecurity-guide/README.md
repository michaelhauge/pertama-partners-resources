# SMB Cybersecurity Guide

**Practical cybersecurity for small and medium businesses without an IT department**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive, non-technical guide to protecting your business from cyber threats. Implement enterprise-grade security in 90 days with affordable tools and clear step-by-step instructions.

---

## The Problem

**Most small businesses are dangerously vulnerable to cyberattacks:**

- 43% of cyberattacks target small businesses
- Average cost of a small business data breach: **$200,000**
- 60% of small businesses **close within 6 months** of a cyberattack
- 68% of small business owners feel vulnerable to cyber threats
- Only 14% rate their ability to mitigate cyber risks as "highly effective"

**Common vulnerabilities:**
- Weak passwords (81% of breaches involve weak or stolen passwords)
- No multi-factor authentication (MFA)
- Employee clicking phishing emails (91% of attacks start with email)
- No backup (ransomware can wipe everything)
- Unsecured devices and networks
- No incident response plan

Most business owners know they need better security, but don't know where to start or can't afford a dedicated IT team.

---

## The Solution: 90-Day Security Roadmap

This guide provides a **phased approach** to securing your business:

### Phase 1: Quick Wins (Week 1-2)
**Impact: 80% risk reduction**

✅ Password manager rollout
✅ Multi-factor authentication (MFA)
✅ Basic phishing training
✅ Inventory your devices and accounts

**Time**: 8-12 hours
**Cost**: $5-8/user/month
**Result**: Blocks most common attacks

### Phase 2: Core Security (Week 3-4)
**Impact: Additional 15% risk reduction**

✅ Endpoint protection on all devices
✅ Email security setup
✅ Full disk encryption
✅ Wi-Fi and network security

**Time**: 12-16 hours
**Cost**: $10-15/user/month
**Result**: Hardened infrastructure

### Phase 3: Resilience (Month 2)
**Impact**: 100% recovery capability

✅ Backup and recovery system
✅ Security policies and documentation
✅ Employee onboarding/offboarding procedures
✅ Phishing simulation program

**Time**: 16-20 hours
**Cost**: $15-20/user/month
**Result**: Can recover from attacks

### Phase 4: Ongoing (Month 3+)
**Impact**: Stay secure over time

✅ Regular security training
✅ Quarterly security audits
✅ Incident response testing
✅ Compliance as needed (PDPA, GDPR, PCI-DSS)

**Time**: 4 hours/month
**Cost**: Same as Phase 3
**Result**: Continuous protection

---

## Who This Is For

This guide is designed for:

✅ **Business owners** with 5-200 employees
✅ **Non-technical leaders** (no IT background required)
✅ **Limited budgets** ($50-500/month for security)
✅ **Mix of office and remote workers**
✅ **Common SaaS tools** (Google Workspace, Microsoft 365, Slack)
✅ **Singapore/Malaysia businesses** (PDPA compliance included)

---

## Who This Is NOT For

This guide may not be suitable if you:

❌ Have a dedicated IT security team
❌ Need full compliance (SOC 2, ISO 27001, FedRAMP)
❌ Work in heavily regulated industries (healthcare with PHI, finance with PCI Level 1)
❌ Have >500 employees (enterprise-scale needs)

For these scenarios, consider hiring a specialized security consultant or CISO.

---

## Quick Decision Tree

**Where should I start?**

```
START: How secure are you today?

├─ "We've been breached or suspect we have"
│  └─ Go to: Incident Response Guide (guides/08-incident-response.md)
│     Action: First 24 hours protocol
│
├─ "We have nothing in place"
│  └─ Go to: Assessment Guide (guides/01-assessment.md)
│     Then: Follow 90-Day Roadmap starting at Week 1
│
├─ "We have passwords and maybe some antivirus"
│  └─ Go to: Assessment Guide (guides/01-assessment.md)
│     Then: Likely start at Week 2-3
│
└─ "We're pretty secure, just need to validate"
   └─ Go to: Assessment Guide (guides/01-assessment.md)
      Action: Get security score, fill gaps, consider compliance
```

---

## Documentation Structure

### 📊 Core Guides

| Guide | Description | Time | Priority |
|-------|-------------|------|----------|
| [TOOLS.md](TOOLS.md) | Security tool comparison matrix (with 2026 pricing) | 30 min | High |
| [COMPLIANCE.md](COMPLIANCE.md) | PDPA, GDPR, PCI-DSS, HIPAA basics | 45 min | Medium |
| [FAQ.md](FAQ.md) | Common questions answered | 15 min | High |

### 📖 Implementation Guides

**Complete guides** with step-by-step instructions, ROI, and real-world examples:

| # | Guide | What You'll Learn | ROI | Priority |
|---|-------|-------------------|-----|----------|
| 01 | [Security Assessment](guides/01-assessment.md) | Assess current security posture, create 90-day plan | - | **START HERE** |
| 02 | [Passwords & Access](guides/02-passwords-access.md) | Password managers, MFA, SSO, least privilege | 80% ↓ account compromise | **Week 1** |
| 03 | [Email & Phishing](guides/03-email-phishing.md) | Phishing prevention, email security, DMARC | 70% ↓ phishing success | **Week 1-2** |
| 04 | [Device Security](guides/04-device-security.md) | Endpoint protection, encryption, MDM, patching | 60% ↓ device breaches | **Week 3** |
| 05 | [Network Security](guides/05-network-security.md) | VPN, firewall, Wi-Fi, home office security | 50% ↓ network intrusion | **Week 3-4** |
| 06 | [Backup & Recovery](guides/06-backup-recovery.md) | 3-2-1 rule, cloud backup, disaster recovery, testing | 100% ransomware recovery | **Month 2** |
| 07 | [Cloud Security](guides/07-cloud-security.md) | Google/M365 hardening, SaaS auditing, shadow IT | 40% ↓ cloud compromise | **Month 2** |
| 08 | [Incident Response](guides/08-incident-response.md) | Breach detection, first 24 hours, recovery | 50% ↓ breach costs | **Month 2-3** |

### 🛠️ Tools & Templates

**Ready-to-use resources** for your business:

| Template | Description | Use Case |
|----------|-------------|----------|
| [Security Policy](templates/security-policy.md) | Company-wide security acceptable use policy | Required for all employees |
| [Onboarding Checklist](templates/onboarding-checklist.md) | New employee security setup | Every new hire |
| [Offboarding Checklist](templates/offboarding-checklist.md) | Employee departure security | Every departure |
| [Vendor Questionnaire](templates/vendor-questionnaire.md) | Third-party security assessment | Before signing vendor contracts |
| [Incident Response Playbook](templates/incident-response.md) | Breach response checklist | When you're breached |

### 🤖 Scripts

| Script | Description | Usage |
|--------|-------------|-------|
| [security-audit.py](scripts/security-audit.py) | Interactive security assessment tool | `python3 scripts/security-audit.py --interactive` |
| [password-audit.sh](scripts/password-audit.sh) | Password strength checker | `bash scripts/password-audit.sh` |

---

## Expected Results

By following this guide, expect:

### Security Improvements
- **Week 1-2**: 80% reduction in common attack vectors
- **Month 1**: 95% reduction in successful breaches
- **Month 2**: 100% recovery capability from ransomware
- **Month 3+**: Continuous protection and compliance readiness

### Cost Savings
- **Prevent breaches**: Avoid $200K average breach cost
- **Lower insurance**: Cyber insurance premiums 20-40% lower
- **Productivity**: 5-10 hours/month saved on security issues
- **Peace of mind**: Sleep better knowing you're protected

### Business Benefits
- Customer trust (show you take security seriously)
- Compliance readiness (PDPA, GDPR when needed)
- Competitive advantage (security as differentiator)
- Scalable security (grows with your business)

### Total Investment

| Expense | Monthly Cost |
|---------|--------------|
| Password manager | $5-8/user |
| Endpoint protection | $5-12/user |
| Email security | $0-5/user (often included) |
| Backup | $7-9/month |
| VPN (if needed) | $0-8/user |
| Security training | $1.50/user ($18/year) |
| **Total** | **$18-45/user/month** |

**For 20 employees**: $360-900/month vs. $200,000 breach cost = **444x ROI**

---

## Common Questions

### "How much should I budget for security?"

**Minimum**: $15-20/user/month (passwords, antivirus, backup)
**Recommended**: $30-45/user/month (add VPN, training, MDM)
**Industry benchmark**: 3-7% of IT budget

For a 20-person company:
- **Year 1**: $7,200-10,800 (includes setup time)
- **Year 2+**: $3,600-5,400 (ongoing only)

### "Do I need a dedicated IT person?"

**Not for 5-50 employees**. This guide is designed for non-technical owners to implement security themselves. Budget 2-4 hours/week initially, then 1-2 hours/week ongoing.

**For 50-200 employees**, consider a part-time IT person or fractional CIO to manage day-to-day.

### "What's the #1 thing I should do first?"

**Password manager + MFA** on all critical accounts. This alone prevents 80% of attacks and takes 2-4 hours to implement.

**See**: [Passwords & Access Guide](guides/02-passwords-access.md)

### "Is free antivirus enough?"

**No**. Free consumer antivirus:
- Lacks endpoint management (can't see all devices)
- No centralized control
- Limited or no support
- Often sells your data

Business endpoint protection costs $5-12/user/month and provides:
- Central management console
- Real-time threat protection
- Support when you need it
- Compliance reporting

**See**: [Device Security Guide](guides/04-device-security.md)

### "How do I know if I've been hacked?"

**Red flags**:
- Unexpected password reset emails
- Unauthorized charges or transactions
- Files encrypted or renamed (ransomware)
- Customers reporting phishing emails from you
- Slow computers or network
- Pop-ups or unfamiliar browser extensions

**If you see any of these**: [Incident Response Guide](guides/08-incident-response.md) (first 24 hours)

---

## Next Steps

Choose your path based on your situation:

### Path A: Emergency (Suspected Breach)
1. **Right now**: [Incident Response Guide](guides/08-incident-response.md)
2. Contain the damage (disconnect affected systems)
3. Contact cyber insurance and legal counsel
4. After recovery: Follow Path B

### Path B: Starting from Scratch (90-Day Plan)
1. **Day 1**: [Security Assessment](guides/01-assessment.md) → Get security score
2. **Week 1-2**: [Passwords & Access](guides/02-passwords-access.md) + [Email Security](guides/03-email-phishing.md)
3. **Week 3-4**: [Device Security](guides/04-device-security.md) + [Network Security](guides/05-network-security.md)
4. **Month 2**: [Backup & Recovery](guides/06-backup-recovery.md) + [Cloud Security](guides/07-cloud-security.md)
5. **Month 3**: [Incident Response](guides/08-incident-response.md) + ongoing monitoring

### Path C: Already Secure (Validation)
1. **Day 1**: [Security Assessment](guides/01-assessment.md) → Get security score
2. Review gaps identified in assessment
3. Fill specific gaps (use relevant guides)
4. Consider compliance: [COMPLIANCE.md](COMPLIANCE.md)
5. Setup ongoing monitoring and training

---

## Related Guides

This guide complements other **Pertama Partners** resources:

- **[AI Implementation Playbook](../ai-implementation-playbook/)** - AI tools data classification aligns with security tiers
- **[SaaS Optimization Guide](../saas-optimization-guide/)** - SaaS audit includes security review and vendor assessment
- **[CRM Migration Guide](../crm-migration-guide/)** - CRM security considerations during migration
- **[n8n SEA Guide](../n8n-sea-guide/)** - Automation security best practices and secrets management

---

## Contributing

This guide is maintained by **Pertama Partners** for the EO/YPO community. We welcome feedback and contributions:

- **Found an error?** Open an issue or submit a PR
- **Tool pricing outdated?** Let us know the current pricing
- **Want to suggest a new section?** Contact us

---

## License

This guide is licensed under the [MIT License](../LICENSE). You're free to use, modify, and distribute it with attribution.

---

**Last Updated**: February 2026
**Version**: 1.0
**Maintained by**: Pertama Partners

**Questions?** Email: resources@pertamapartners.com
