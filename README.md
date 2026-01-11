# Vibe Holdings Oy — Board Minutes Repository

This repository maintains corporate governance documents for **Vibe Holdings Oy**, a Finnish private limited company (osakeyhtiö).

## Purpose

This repository provides:
- **Version-controlled governance documents** — Complete audit trail of all board and shareholder decisions
- **Standardised templates** — Consistent formatting across all corporate documents
- **Legal compliance** — Documents structured to comply with Finnish Companies Act (osakeyhtiölaki 624/2006)
- **Easy search and reference** — Git-based search across all historical decisions

## Repository Structure

```
├── CLAUDE.md                          # Comprehensive usage guide for creating documents
├── README.md                          # This file
├── .gitignore                         # Git ignore patterns
│
├── templates/                         # Document templates
│   ├── board-meeting.md              # Board meeting minutes template
│   ├── written-resolution.md         # Written resolution template
│   ├── shareholders-meeting-agm.md   # Annual GM minutes template
│   └── shareholders-meeting-egm.md   # Extraordinary GM minutes template
│
├── snippets/                          # Pre-written resolution snippets
│   ├── options/                      # Option plan adoption, issuance, exercise
│   ├── shares/                       # Share issues, transfers, convertible loans
│   ├── directors/                    # Director appointments, resignations, CEO, signatory rights
│   ├── financial/                    # Annual accounts, dividends, auditor, loans
│   ├── administrative/               # Powers of attorney, bank mandates, office changes
│   └── governance/                   # Related party transactions, conflicts, committees
│
├── minutes/                           # Actual meeting minutes and resolutions
│   └── YYYY/                         # Organized by year
│       └── YYYY-MM-DD-[type].md     # Individual minute files
│
├── reference/                         # Current company data
│   ├── company-details.md            # Company information, Y-tunnus, registered office
│   ├── share-capital.md              # Share capital, shareholders, equity
│   ├── option-plans.md               # Option plans, grants, exercises
│   ├── directors-register.md         # Current and historical directors
│   └── authorisations.md             # Active shareholder authorisations to board
│
└── .claude/                           # Claude Code automation commands
    └── commands/
        ├── new-board-meeting.md      # Create board meeting minutes
        ├── new-written-resolution.md # Create written resolution
        ├── new-agm.md                # Create AGM minutes
        └── new-egm.md                # Create EGM minutes
```

## Getting Started

### First Steps

1. **Read CLAUDE.md** — Comprehensive guide on using this repository
2. **Fill in reference files** — Update `/reference/` with your company's actual data:
   - `company-details.md` — Y-tunnus, registered office, financial year
   - `share-capital.md` — Current share capital and shareholders
   - `option-plans.md` — Active option plans (if any)
   - `directors-register.md` — Current board members
   - `authorisations.md` — Active shareholder authorisations (if any)

3. **Review templates and snippets** — Familiarise yourself with available templates and snippets

### Creating Documents

#### Using Claude Code (Recommended)

If using Claude Code with this repository:

- Use `.claude/commands/` for automated document creation
- Commands will guide you through the process step-by-step
- Examples:
  - Create board meeting: Use command `new-board-meeting`
  - Create written resolution: Use command `new-written-resolution`
  - Create AGM: Use command `new-agm`
  - Create EGM: Use command `new-egm`

#### Manual Creation

1. **Select appropriate template** from `/templates/`
2. **Copy template content** to new file in `/minutes/YYYY/`
3. **Fill in placeholders** (marked with `{{PLACEHOLDER}}`)
4. **Insert relevant snippets** from `/snippets/` for resolutions
5. **Verify data** against `/reference/` files
6. **Save** with filename format: `YYYY-MM-DD-[type].md`
7. **Update reference files** if company data changed

## Document Types

### Board Meeting Minutes (`board-meeting.md`)

Full board meeting with physical/virtual attendance, discussion, and resolutions.

**When to use**: Regular board meetings, strategic discussions, matters requiring deliberation

**Filename example**: `2025-03-15-board-meeting.md`

### Written Resolutions (`written-resolution.md`)

Board decisions without a meeting (OYL 6:3). Requires **unanimous approval** of all directors.

**When to use**: Routine matters, time-sensitive decisions between meetings, matters with pre-existing consensus

**Filename example**: `2025-03-20-written-resolution.md`

### Annual General Meeting (`agm.md`)

Mandatory yearly shareholder meeting within 6 months of financial year end.

**When to use**: Adopting accounts, declaring dividend, electing directors and auditor, granting discharge

**Filename example**: `2025-04-10-agm.md`

### Extraordinary General Meeting (`egm.md`)

Special shareholder meeting for specific urgent matters.

**When to use**: Share issues, Articles amendments, urgent decisions outside regular AGM cycle

**Filename example**: `2025-06-05-egm.md`

## Legal Compliance

This repository is designed to help maintain compliance with:

- **Finnish Companies Act** (osakeyhtiölaki 624/2006)
- **Finnish Accounting Act** (kirjanpitolaki 1336/1997)
- **Corporate governance best practices**

### Key Requirements

- **Minutes retention**: Permanent retention required (OYL 2:10)
- **PRH filings**: Many decisions must be filed with Finnish Patent and Registration Office within 2 months
- **AGM timing**: Must be held within 6 months of financial year end (OYL 5:3)
- **Board quorum**: More than half of directors must be present (OYL 6:6)
- **Shareholder notice**: 1 week to 2 months before general meetings (OYL 5:19)

See CLAUDE.md for detailed legal requirements.

## Security and Access

⚠️ **Confidential Information**

This repository contains sensitive corporate information:
- Personal data of directors and shareholders
- Financial information
- Strategic decisions
- Pending transactions

**Access control**:
- Limit access to authorised persons only (directors, officers, company secretary, legal counsel)
- Use private repository
- Enable two-factor authentication
- Regularly review access permissions

## Git Workflow

### Branching Strategy

- **Main branch**: Approved, signed documents only
- **Draft branches**: Use for drafting (e.g., `draft/2025-03-15-board-meeting`)
- **Pull requests**: Review before merging to main

### Commit Messages

Use clear, descriptive messages:
- `Add: 2025-03-15 board meeting minutes`
- `Update: directors-register.md with new appointment`
- `Add: option issuance snippet`

### Searching History

Git provides complete audit trail:
- View all changes: `git log --all -- [file]`
- Search across history: `git log -S "search term"`
- Revert if needed: `git revert [commit]`

## External Filings

Many decisions require filing with PRH:

| Decision Type | Filing Deadline | Form |
|---------------|-----------------|------|
| Director appointment/resignation | 2 months | YTJ2 |
| Managing Director appointment | 2 months | YTJ2 |
| Signatory rights changes | 2 months | YTJ2 |
| Articles amendments | 2 months | YTJ2 + Articles |
| Share capital changes | 2 months | YTJ2 |
| Financial statements | [Varies by company size] | XBRL |

Use PRH's online service: [ytj.fi](https://www.ytj.fi)

## Support and Maintenance

### Questions

- **Finnish company law**: Consult qualified Finnish legal counsel
- **Repository usage**: See CLAUDE.md
- **Document formatting**: Refer to templates and CLAUDE.md

### Maintenance Schedule

**Monthly**:
- Review upcoming board meetings and prepare agendas
- Check for upcoming vesting events (if option plans active)

**Quarterly**:
- Review reference files for accuracy
- Check authorisation expiry dates

**Annually**:
- Prepare for AGM (within 6 months of FY end)
- Review and renew expiring authorisations at AGM
- Update director insurance if applicable
- Archive previous year's minutes

## About Vibe Holdings Oy

**Company**: Vibe Holdings Oy
**Type**: Private limited company (yksityinen osakeyhtiö)
**Jurisdiction**: Finland
**Governing Law**: Finnish Companies Act (osakeyhtiölaki 624/2006)

For detailed company information, see `/reference/company-details.md`.

---

**Disclaimer**: This repository is a tool for maintaining corporate records. It does not constitute legal advice. Consult qualified Finnish legal counsel for specific legal questions.

**Last updated**: 10.01.2026
