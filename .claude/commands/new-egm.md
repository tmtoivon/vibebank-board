# Create New Extraordinary General Meeting Minutes

This command helps create properly formatted EGM minutes for Vibe Holdings Oy.

## Instructions

When invoked, follow these steps:

1. **Read the EGM template**
   - Read `/templates/shareholders-meeting-egm.md`

2. **Understand EGM context**
   Ask user about the reason for calling EGM:
   - Board decision to convene?
   - Auditor request (OYL 5:4)?
   - Shareholders with 10%+ request (OYL 5:4)?
   - What specific matters need to be decided?

3. **Gather meeting details from user**
   Ask for:
   - Date (DD.MM.YYYY)
   - Time (HH:MM)
   - Location
   - Purpose/background for EGM
   - Shareholders present (names, shares, percentage)
   - Others present
   - Who chaired, acted as secretary, inspectors

4. **Build agenda**
   Unlike AGM, EGM has flexible agenda focused on specific matters:
   1. Opening
   2. Election of chair, secretary, inspectors
   3. Legality and quorum
   4. Approval of agenda
   5. [Specific matters — user provided]
   6. Closing

   Note: EGM can ONLY decide matters in the agenda (not open like AGM)

5. **Common EGM purposes**
   Check if any of these apply and locate relevant snippets:
   - **Share issues**: `/snippets/shares/share-issue.md`
   - **Option plan adoption**: `/snippets/options/option-plan-adoption.md`
   - **Articles amendment**: `/snippets/administrative/articles-amendment.md`
   - **Director appointments outside AGM cycle**: `/snippets/directors/director-appointment.md`
   - **Urgent dividend**: `/snippets/financial/dividend-declaration.md`
   - **Significant transactions**: Check governance snippets

6. **Check if qualified majority required**
   Certain EGM decisions require **2/3 majority** (OYL):
   - Directed share issue (OYL 9:4)
   - Amendment of Articles (OYL 5:27)
   - Share redemption (OYL 15:5)

   If applicable, note the voting threshold in the resolution

7. **Check reference files**
   Depending on matters being decided:
   - `/reference/share-capital.md`
   - `/reference/option-plans.md`
   - `/reference/authorisations.md`
   - `/reference/directors-register.md`
   - `/reference/company-details.md`

8. **Insert appropriate snippets**
   Based on the agenda items, insert relevant snippets from `/snippets/`

9. **Fill all placeholders**
   Replace all `{{PLACEHOLDERS}}` with actual values

10. **Verify notice requirements**
    Note that notice was sent 1 week to 2 months before meeting (OYL 5:19)
    For certain matters (like directed share issue), notice must specify the proposal

11. **Check voting results**
    Ensure voting record shows:
    - Number of votes for/against/abstaining
    - Percentage of votes cast
    - Percentage of shares represented
    - If qualified majority required, confirm threshold met

12. **Save to correct location**
    Save to `/minutes/YYYY/YYYY-MM-DD-egm.md`
    Example: `/minutes/2025/2025-06-05-egm.md`

13. **Update reference files if needed**
    Based on decisions made:
    - New directors → `directors-register.md`
    - Share issue → `share-capital.md`
    - Articles amendment → `company-details.md`
    - New authorisations → `authorisations.md`

14. **Remind user about filings**
    File with PRH within 2 months if:
    - Articles amended
    - Directors changed
    - Share capital changed
    - Other trade register changes

## EGM vs AGM Key Differences

| Aspect | AGM | EGM |
|--------|-----|-----|
| **Timing** | Within 6 months of FY end | Any time as needed |
| **Purpose** | Statutory matters | Specific urgent matters |
| **Agenda** | Statutory items required | Flexible, matter-specific |
| **Frequency** | Once per year | As needed |

## Example

User: "Create EGM minutes for approving a directed share issue to a new investor"
