# GTM Revenue OS

**Owner:** Revenue Leadership  
**Version:** 1.0  
**Last Updated:** 2026-06-11  
**Status:** Active  
**Audience:** Sales, Business Development, Marketing, Partnerships, Customer Success, Executive Leadership  

---

## Purpose

This repository is the single source of truth for go-to-market execution across sales, business development, partnerships, sales enablement, market research, competitive intelligence, and proposal development.

It supports three primary customer segments:

1. SMB SaaS
2. Mid-Market SaaS
3. MSP / Managed Services Providers

The repository has two jobs:

1. **Internal Operating System**  
   Used by Scaletics and affiliated GTM teams to execute consistently.

2. **Client Template System**  
   Adapted for client engagements where SaaS, AI, MSP, cybersecurity, cloud, and technology services companies need repeatable revenue infrastructure.

---

## Who Should Use This Repo?

| Role | Primary Sections |
|---|---|
| Founder / CEO | `01-gtm-strategy`, `10-proposals-and-sows`, `12-governance` |
| Head of Sales | `02-sales-playbooks`, `03-sales-enablement`, `07-competitive-intelligence` |
| Account Executive | `02-sales-playbooks`, `03-sales-enablement`, `10-proposals-and-sows` |
| SDR / BDR | `02-sales-playbooks`, `03-sales-enablement`, `06-market-research` |
| BD Lead | `04-business-development`, `08-partner-programs`, `05-collateral` |
| Marketing Lead | `01-gtm-strategy`, `05-collateral`, `06-market-research` |
| Client Delivery Lead | `11-client-template-kit`, `12-governance`, `10-proposals-and-sows` |

---

## Segment Navigation

### SMB SaaS

Use this path when the target customer has a simple buying cycle, founder-led selling, self-service adoption, and urgency around conversion, activation, or churn.

Start here:

```text
01-gtm-strategy/segment-overlays/smb-saas.md
02-sales-playbooks/segment-overlays/smb-saas-sales-motion.md
03-sales-enablement/qualification-checklists/smb-saas-checklist.md
```

### Mid-Market SaaS

Use this path when the target customer has a 3 to 6 month sales cycle, multiple stakeholders, ROI scrutiny, security concerns, procurement, and business-case requirements.

Start here:

```text
01-gtm-strategy/segment-overlays/mid-market-saas.md
02-sales-playbooks/segment-overlays/mid-market-saas-sales-motion.md
03-sales-enablement/qualification-checklists/mid-market-saas-checklist.md
```

### MSP / Managed Services

Use this path when the target customer sells recurring managed services, IT support, cybersecurity, cloud, Microsoft, hosting, infrastructure, or compliance offerings.

Start here:

```text
01-gtm-strategy/segment-overlays/msp.md
02-sales-playbooks/segment-overlays/msp-sales-motion.md
03-sales-enablement/qualification-checklists/msp-checklist.md
```

---

## Repository Principles

1. **One source of truth**  
   Do not create duplicate copies of core GTM documents.

2. **Segment overlays, not segment silos**  
   Segment-specific nuance belongs in `segment-overlays/`.

3. **Templates must be deployable**  
   Every template should be usable by a sales or BD professional with minimal editing.

4. **Keep docs current**  
   Every core document must include owner, version, last updated date, status, and review cadence.

5. **Separate internal content from client-ready content**  
   Client-safe versions belong in `11-client-template-kit/`.

---

## First-Time Workflow

### Internal GTM Setup

1. Read `00-start-here/how-to-use-this-repo.md`
2. Confirm the target segment in `00-start-here/segment-routing-guide.md`
3. Define ICP using `01-gtm-strategy/icp-and-segmentation.md`
4. Align messaging using `01-gtm-strategy/positioning-and-messaging.md`
5. Configure the sales process using `02-sales-playbooks/sales-process.md`
6. Deploy templates from `03-sales-enablement/`
7. Track major changes in `changelog.md`

### Client Engagement Setup

1. Complete `11-client-template-kit/client-discovery-intake.md`
2. Select the correct segment overlay
3. Copy relevant files into the client workspace
4. Replace internal examples with client-specific details
5. Review client-ready docs against `11-client-template-kit/client-customization-guide.md`
6. Finalize deliverables through proposal or SOW process

---

## Maintenance Cadence

| Asset Type | Review Frequency | Owner |
|---|---:|---|
| Sales process | Monthly | Head of Sales |
| Messaging | Monthly | GTM Lead |
| Objection handling | Biweekly | Sales Lead |
| Competitive intelligence | Monthly | BD / Marketing |
| Proposal templates | Quarterly | Revenue Ops |
| Partner program docs | Quarterly | BD Lead |
| Case studies | Quarterly | Marketing |
| Governance docs | Quarterly | Operations |

---

## Contribution Process

All updates should follow:

```text
12-governance/contribution-guide.md
```

No major GTM, pricing, positioning, or sales-process change should be merged without review from the document owner.
