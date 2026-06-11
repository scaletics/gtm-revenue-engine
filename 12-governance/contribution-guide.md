# Contribution Guide

**Owner:** Operations
**Version:** 1.0
**Last Updated:** 2026-06-11
**Status:** Active
**Review Cadence:** Quarterly
**Audience:** All Contributors
**Client Reuse:** Internal Only

## Purpose

This guide explains how team members should update, improve, and maintain the GTM Revenue OS.

The goal is to keep the repository current, accurate, usable, and trusted.

## Contribution Rules

### 1. Every Core Document Needs Metadata

Every production document must include:

```text
Owner
Version
Last Updated
Status
Review Cadence
Audience
Client Reuse
```

### 2. Do Not Duplicate Core Content

Do not create separate versions of the same core process for each segment.

Use this model:

```text
Core process document
+
Segment overlay
```

### 3. Use Clear File Names

Use lowercase file names with hyphens.

Correct:

```text
discovery-framework.md
partner-qualification-scorecard.md
```

Incorrect:

```text
Discovery Framework Final v3 NEW.md
```

### 4. Mark Document Status Clearly

Use one of the following statuses:

- Draft
- Active
- Needs Review
- Deprecated
- Archived

### 5. Update the Changelog

Any meaningful change must be recorded in `changelog.md`.

Include:

- Date
- File changed
- Owner
- Summary of change
- Reason for change, if not obvious

### 6. Review Before Major Changes

Major changes require owner review.

Major changes include:

- ICP changes
- Pricing changes
- Sales process changes
- Proposal structure changes
- Positioning changes
- Partner strategy changes
- Client template changes

## Pull Request Checklist

Before submitting an update:

- [ ] Metadata is updated.
- [ ] File name follows naming convention.
- [ ] Content is clear and usable.
- [ ] Segment differences are documented.
- [ ] Internal-only content is not included in client templates.
- [ ] Changelog entry is added.
- [ ] Document owner is tagged for review.

## Review Cadence

| Content Type | Review Frequency |
|---|---:|
| Sales playbooks | Monthly |
| Messaging | Monthly |
| Objection handling | Biweekly |
| Email sequences | Monthly |
| Competitive battlecards | Monthly |
| Proposals | Quarterly |
| Partner docs | Quarterly |
| Governance | Quarterly |

## Client-Safe Content Rules

Before adapting a document for a client:

- Remove internal pricing unless approved.
- Remove internal customer names unless public and approved.
- Remove private CRM notes.
- Remove internal operating assumptions.
- Replace Scaletics-specific language with client-specific language.
- Confirm the document is marked Client-Customizable or Client-Safe.

## Archive Policy

Archive a document when:

- It is no longer accurate.
- It has been replaced.
- It refers to an old offer, market, or segment.
- It contains outdated pricing.
- It is no longer used by the team.

Move archived documents to:

```text
archive/YYYY/
```

Do not delete unless approved by the repository owner.

## Repo Health Rule

Every active document should support one of the following outcomes:

- Sell
- Position
- Qualify
- Propose
- Partner
- Research
- Govern
- Deliver client work

If it does not support one of those outcomes, it should not be active.
