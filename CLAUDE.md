# Vibe Holdings Oy — Board Minutes Repository

## Repository Purpose

This repository maintains corporate governance documents for **Vibe Holdings Oy**, a Finnish private limited company (yksityinen osakeyhtiö). All board meeting minutes, shareholder meeting minutes, and written resolutions are maintained using markdown files under git version control to ensure:

- Complete audit trail of all corporate decisions
- Standardised formatting across all governance documents
- Easy searchability and reference
- Proper compliance with Finnish Companies Act requirements

## Legal Framework

This repository follows the **Finnish Companies Act** (osakeyhtiölaki 624/2006, "OYL"). Key chapters:

- **Chapter 5**: General meeting (yhtiökokous) — procedures, notice requirements, resolutions
- **Chapter 6**: Board of directors (hallitus) and managing director (toimitusjohtaja) — duties, decision-making, written resolutions
- **Chapter 9**: Share issue (osakeanti) — procedures, pre-emptive rights, directed issues
- **Chapter 10**: Other equity instruments including options (optio-oikeudet) — issuance, terms, exercise
- **Chapter 13**: Financial statements and audit
- **Chapter 14**: Distribution of profit

## Document Creation Rules

### Basic Workflow

1. **Always start with templates** from `/templates/`
2. **Insert relevant snippets** from `/snippets/` for specific resolutions
3. **Check reference files** in `/reference/` for current company data before drafting
4. **Save to `/minutes/YYYY/`** with proper filename format
5. **Update reference files** when resolutions change company data (e.g., new directors, share issues)

### Filename Format

All minutes must follow this format:

```
YYYY-MM-DD-<type>.md
```

Examples:
- `2025-03-15-board-meeting.md`
- `2025-03-20-written-resolution.md`
- `2025-04-10-agm.md`
- `2025-06-05-egm.md`

### Document Numbering

- **Board meetings**: Sequential within calendar year (1/2025, 2/2025, etc.)
- **Written resolutions**: Format `YYYY-WR-NNN` (2025-WR-001, 2025-WR-002, etc.)
- **Resolutions within documents**: Numbered sequentially (Resolution 1, Resolution 2, etc.)

## Formatting Standards

### Language and Terminology

- **Primary language**: British English
- **Finnish legal terms**: Show in parentheses on first use
  - Example: "The Board of Directors (hallitus) resolved..."
  - Example: "The Annual General Meeting (varsinainen yhtiökokous) approved..."
- **Common Finnish terms to use**:
  - Board of Directors = hallitus
  - Managing Director / CEO = toimitusjohtaja
  - Annual General Meeting = varsinainen yhtiökokous (AGM)
  - Extraordinary General Meeting = ylimääräinen yhtiökokous (EGM)
  - Share issue = osakeanti
  - Options = optio-oikeudet
  - Articles of Association = yhtiöjärjestys
  - Business ID = Y-tunnus
  - Pre-emptive right = etuoikeus

### Date and Number Formatting

- **Dates**: DD.MM.YYYY format (e.g., 15.03.2025)
- **Currency**: EUR (e.g., EUR 50 000, EUR 2.50)
- **Numbers**: Space as thousands separator (e.g., 10 000, 1 250 000)
- **Percentages**: Standard format (e.g., 5.5%, 100%)

### Names and Titles

- **First mention**: Full name and title
  - Example: "Matti Virtanen, Chairman of the Board"
- **Subsequent mentions**: Surname only
  - Example: "Virtanen noted that..."
- **Directors list**: Alphabetical by surname or by role (Chair, members)

### Resolution Formatting

Each resolution should:
1. Have a clear number (Resolution 1, Resolution 2, etc.)
2. State the matter being decided
3. Include the actual resolution text (often in italic or bold)
4. Note the voting result ("Approved unanimously" or detailed voting record)
5. Include any required follow-up actions or filing requirements

## Quorum and Voting Rules

### Board of Directors (OYL 6:6)

- **Quorum**: More than half of directors must be present (unless articles specify otherwise)
- **Decision-making**: Simple majority of votes cast
- **Casting vote**: Chair has casting vote in case of tie (if provided in articles)
- **Written resolutions** (OYL 6:3): Permitted unless articles prohibit; requires unanimous approval of all directors

### General Meetings

- **Quorum**: No statutory quorum requirement for Oy (unless specified in articles)
- **Voting**: Each share carries one vote (unless articles specify share classes with different voting rights)
- **Majority**: Simple majority unless OYL or articles require qualified majority
- **Qualified majority required for**:
  - Amendment of articles (⅔ of votes and shares represented) (OYL 5:27)
  - Directed share issue (⅔ of votes and shares represented) (OYL 9:4)
  - Redemption of shares (⅔ of votes and shares represented) (OYL 15:5)

## Required Signatures

### Documents Requiring Signatures

- **Board meeting minutes**: Chair and secretary (at minimum); good practice: all attendees
- **Written resolutions**: All board members must sign
- **General meeting minutes**: Chair, secretary, and minutes inspectors
- **Signature method**: Wet signatures are traditional; digital signatures acceptable if meeting Finnish e-signature requirements

### PRH Filings

The following decisions require filing with Finnish Patent and Registration Office (PRH):

- Director appointments and resignations
- Managing Director appointment and resignation
- Changes to signatory rights
- Changes to articles of association
- Share capital increases/decreases
- Changes to registered office or business address
- Business name changes

**Filing deadline**: Generally within 2 months of decision

## Using Templates

### Available Templates

1. **`/templates/board-meeting.md`** — Full board meeting minutes
2. **`/templates/written-resolution.md`** — Board written resolution (OYL 6:3)
3. **`/templates/shareholders-meeting-agm.md`** — Annual General Meeting
4. **`/templates/shareholders-meeting-egm.md`** — Extraordinary General Meeting

### Template Variables

Templates use `{{PLACEHOLDER}}` syntax for variable content:
- `{{DATE}}` — Meeting/resolution date
- `{{TIME}}` — Meeting start time
- `{{LOCATION}}` — Meeting location
- `{{RESOLUTIONS}}` — Placeholder for resolution content from snippets
- `{{NAME}}`, `{{ROLE}}`, etc. — Person-specific data

## Using Snippets

Snippets are pre-written resolution templates for common corporate actions. They are organised by category:

### Categories

- **`/snippets/options/`** — Option plan adoption, issuance, exercise
- **`/snippets/shares/`** — Share issues, transfers, convertible loans
- **`/snippets/directors/`** — Appointments, resignations, signatory rights
- **`/snippets/financial/`** — Annual accounts, dividends, auditor appointments
- **`/snippets/administrative/`** — Powers of attorney, bank mandates, office changes
- **`/snippets/governance/`** — Related party transactions, conflicts of interest

### How to Use Snippets

1. Identify the type of resolution needed
2. Find matching snippet in appropriate category
3. Copy snippet content into template at `{{RESOLUTIONS}}` placeholder
4. Fill in all `{{PLACEHOLDERS}}` with actual data
5. Verify data against `/reference/` files
6. Adjust numbering to match document sequence

## Reference Files

The `/reference/` directory maintains current company data. **Always check these files before drafting documents.**

### File Descriptions

- **`company-details.md`** — Basic company information (Y-tunnus, registered office, incorporation date)
- **`share-capital.md`** — Current share capital, number of shares, shareholder register summary
- **`option-plans.md`** — All option plans, pools, grants, and remaining allocations
- **`directors-register.md`** — Current and historical board members, appointment dates
- **`authorisations.md`** — Active shareholder authorisations to board (share issues, option issues, buybacks)

### Updating Reference Files

After resolutions that change company data:
- **New director appointed** → Update `directors-register.md`
- **Share issue approved** → Update `share-capital.md`
- **Options granted** → Update `option-plans.md`
- **New authorisation granted** → Update `authorisations.md`
- **Registered office changed** → Update `company-details.md`

## Notice Requirements

### Board Meetings

- **Notice**: No statutory requirement; practice varies by company
- **Form**: Typically by email or board portal
- **Content**: Date, time, location, proposed agenda

### General Meetings (OYL 5:19)

- **Timing**: Earliest 2 months before, latest 1 week before meeting
- **Form**: Written notice to each shareholder at registered address
- **Content**: Agenda items, proposed resolutions, time, location
- **Special rules**:
  - Notice for AGM must specify statutory agenda items
  - Certain resolutions (e.g., directed share issue) require specific notice of the proposal

### Annual General Meeting Timing (OYL 5:3)

- **Deadline**: Within 6 months of financial year end
- **Example**: Financial year ends 31.12.2024 → AGM by 30.06.2025

## Common Corporate Actions

### Share Issues

**Legal basis**: OYL Chapter 9

**Process**:
1. Board proposes share issue to general meeting (or exercises existing authorisation)
2. General meeting approves (or board decides under authorisation)
3. Subscription period opens
4. Subscriptions received and approved
5. Payment deadline
6. Filing with PRH
7. Update `share-capital.md`

**Key considerations**:
- Pre-emptive rights (etuoikeus) — shareholders have right to subscribe pro rata unless waived
- Directed issue requires ⅔ majority and "weighty financial reason"
- Subscription price must be at least nominal value (if par value shares)

### Option Issuances

**Legal basis**: OYL Chapter 10

**Process**:
1. General meeting approves option plan and pool
2. General meeting grants authorisation to board to issue options (max 5 years)
3. Board issues options under authorisation to specific recipients
4. Options vest per plan terms
5. Recipients exercise options during exercise window
6. Company issues shares upon exercise
7. Update `option-plans.md` and `share-capital.md`

**Key considerations**:
- Options are equity instruments, not share-based payments for accounting
- Exercise price methodology must be specified in plan
- Dilution effect should be disclosed
- PRH registration required after share issuance upon exercise

### Director Appointments

**Legal basis**: OYL 6:4

**Process**:
1. General meeting elects directors (typically at AGM)
2. Directors take office immediately unless later date specified
3. Term runs until end of next AGM (unless articles provide otherwise)
4. File change with PRH within 2 months
5. Update `directors-register.md`

**Key considerations**:
- Minimum one director required for Oy; three if auditor waived
- No residency requirement for directors in Finland
- Good practice to assess and record independence

## Git Workflow

### Branching Strategy

- **Main branch**: Approved, signed documents only
- **Draft branches**: Use feature branches for drafting (e.g., `draft/2025-03-15-board-meeting`)
- **Review process**: PR review before merging to main

### Commit Messages

Use clear, descriptive messages:
- `Add: 2025-03-15 board meeting minutes`
- `Update: directors-register.md with new appointment`
- `Add: option issuance snippet`

### File History

Git history provides complete audit trail:
- View all changes to any document
- See who made changes and when
- Revert to previous versions if needed

## Data Privacy and Security

### Confidential Information

This repository contains confidential corporate information:
- Personal data of directors and shareholders
- Financial information
- Strategic decisions

**Access control**: Limit repository access to authorised persons only (directors, officers, company secretary, legal counsel)

### Repository Security

- Use private repository
- Enable two-factor authentication
- Regularly review access permissions
- Consider encryption for sensitive documents

## External Filing and Archiving

### PRH Filings

After decisions requiring PRH filing:
1. Prepare official filing form
2. Attach board/GM minutes as supporting document
3. Submit electronically via PRH's online service
4. Record filing date and reference number in minutes

### Long-term Archiving

**Retention requirement**: OYL 2:10 requires companies to keep minutes permanently

Ensure:
- Regular backups of repository
- Offsite backup storage
- Succession plan for repository access

## Questions or Issues?

For questions about:
- **Finnish company law**: Consult qualified Finnish legal counsel
- **Repository structure**: See `.claude/commands/` for automated workflows
- **Document formatting**: Refer to templates and this guide

---

**Last updated**: 10.01.2026
**Maintained by**: Vibe Holdings Oy Board Secretary
