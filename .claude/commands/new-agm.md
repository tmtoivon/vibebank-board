# Create New Annual General Meeting Minutes

This command helps create properly formatted AGM minutes for Vibe Holdings Oy.

## Instructions

When invoked, follow these steps:

1. **Read the AGM template**
   - Read `/templates/shareholders-meeting-agm.md`

2. **Check company details and financial year**
   - Read `/reference/company-details.md` for financial year dates
   - Verify AGM is within 6 months of FY end (OYL 5:3 requirement)
   - Example: FY ends 31.12.2024 → AGM must be by 30.06.2025

3. **Gather meeting details from user**
   Ask for:
   - Date (DD.MM.YYYY)
   - Time (HH:MM)
   - Location
   - Shareholders present (names, number of shares, percentage)
   - Others present (directors, auditor, advisors)
   - Who chaired the meeting
   - Who acted as secretary
   - Who were minutes inspectors

4. **Prepare statutory agenda items**
   The AGM must include these statutory items (OYL 5:3):
   1. Opening
   2. Election of chair, secretary, inspectors
   3. Legality and quorum
   4. Approval of agenda
   5. Presentation of accounts and auditor's report
   6. Adoption of financial statements
   7. Resolution on profit/loss and dividend
   8. Discharge of directors and MD
   9. Determination of number of directors (if applicable)
   10. Determination of remuneration
   11. Election of directors
   12. Election of auditor

5. **Check reference files for data**
   - `/reference/company-details.md` — Financial year
   - `/reference/share-capital.md` — Distributable equity for dividend decision
   - `/reference/directors-register.md` — Current directors
   - Latest approved financial statements

6. **Ask user for decisions on each item**
   For each agenda item, gather:
   - What was decided
   - Voting results
   - Any discussion points

7. **Insert appropriate snippets**
   Use snippets from `/snippets/financial/`:
   - `annual-accounts-approval.md`
   - `dividend-declaration.md` (if dividend declared)
   - `auditor-appointment.md` (or waiver)

   Use snippets from `/snippets/directors/`:
   - `director-appointment.md` (for new/re-elected directors)

8. **Fill all placeholders**
   Replace all `{{PLACEHOLDERS}}` with actual data

9. **Check notice requirements**
   Note in minutes that notice was sent 1 week to 2 months before meeting (OYL 5:19)

10. **Save to correct location**
    Save to `/minutes/YYYY/YYYY-MM-DD-agm.md`
    Example: `/minutes/2025/2025-04-10-agm.md`

11. **Update reference files**
    After AGM, update:
    - `/reference/directors-register.md` if board composition changed
    - `/reference/share-capital.md` if dividend declared
    - `/reference/company-details.md` if auditor changed
    - `/reference/authorisations.md` if new authorisations granted

12. **Remind user about filings**
    Remind to:
    - File changes with PRH within 2 months (directors, auditor)
    - File financial statements with PRH

## AGM Timing Reminder

**Critical**: AGM must be held within **6 months** of financial year end.
Miss this deadline → serious compliance issue.

## Example

User: "Create AGM minutes for the 2024 financial year AGM"
