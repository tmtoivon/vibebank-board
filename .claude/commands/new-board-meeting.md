# Create New Board Meeting Minutes

This command helps create properly formatted board meeting minutes for Vibe Holdings Oy.

## Instructions

When invoked, follow these steps:

1. **Read the board meeting template**
   - Read `/templates/board-meeting.md`

2. **Check current board composition**
   - Read `/reference/directors-register.md` to get current board members

3. **Determine meeting number**
   - Check `/minutes/YYYY/` for latest meeting number this year
   - Assign next sequential number (e.g., if last was 3/2025, this is 4/2025)

4. **Gather meeting details from user**
   Ask the user for:
   - Date of meeting (DD.MM.YYYY)
   - Time (HH:MM)
   - Location
   - Directors present (by name)
   - Directors absent (if any, with reason)
   - Others present (CEO, secretary, advisors, etc.)
   - Who chaired the meeting
   - Who acted as secretary

5. **Gather agenda items**
   Ask the user what matters were discussed and decided.
   For each agenda item, ask if there's a relevant snippet in `/snippets/` that matches.

6. **Insert appropriate snippets**
   - Search `/snippets/` for snippets matching the agenda items
   - Insert snippets at the `{{RESOLUTIONS}}` placeholder
   - Fill in placeholders with actual data

7. **Check reference files for data**
   Before finalizing, check:
   - `/reference/share-capital.md` for current share information
   - `/reference/option-plans.md` for option plan details
   - `/reference/directors-register.md` for director information
   - `/reference/authorisations.md` for valid authorisations
   - `/reference/company-details.md` for company information

8. **Fill all placeholders**
   Replace all `{{PLACEHOLDERS}}` with actual values

9. **Verify quorum**
   Confirm that more than half of directors are present (per OYL 6:6)

10. **Save to correct location**
    Save to `/minutes/YYYY/YYYY-MM-DD-board-meeting.md`
    Example: `/minutes/2025/2025-03-15-board-meeting.md`

11. **Update reference files if needed**
    If the meeting made decisions that affect company data:
    - New director → update `directors-register.md`
    - Options granted → update `option-plans.md`
    - Share issue → update `share-capital.md`
    - Signatory rights → update `directors-register.md`

## Example

User: "Create board meeting minutes for meeting held today"