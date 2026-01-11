# Create New Written Resolution

This command helps create properly formatted written board resolutions for Vibe Holdings Oy.

## Instructions

When invoked, follow these steps:

1. **Read the written resolution template**
   - Read `/templates/written-resolution.md`

2. **Check current board composition**
   - Read `/reference/directors-register.md` to get ALL current board members
   - **Important**: ALL directors must approve written resolutions (OYL 6:3)

3. **Determine resolution number**
   - Check `/minutes/YYYY/` for latest written resolution this year
   - Format: YYYY-WR-NNN (e.g., 2025-WR-001, 2025-WR-002)
   - Assign next sequential number

4. **Gather resolution details from user**
   Ask the user for:
   - Date of resolution
   - What matters are being resolved
   - Confirm ALL directors have approved

5. **Match resolutions to snippets**
   For each matter being resolved:
   - Check if there's a relevant snippet in `/snippets/`
   - Insert appropriate snippets at `{{RESOLUTIONS}}` placeholder

6. **Check reference files**
   Verify data against:
   - `/reference/share-capital.md`
   - `/reference/option-plans.md`
   - `/reference/authorisations.md`
   - `/reference/company-details.md`

7. **Fill all placeholders**
   Replace all `{{PLACEHOLDERS}}` with actual values

8. **List ALL directors for approval**
   Ensure all current directors are listed with checkmarks indicating approval

9. **Save to correct location**
   Save to `/minutes/YYYY/YYYY-MM-DD-written-resolution.md`
   Example: `/minutes/2025/2025-03-20-written-resolution.md`

10. **Update reference files if needed**
    If resolutions affect company data, update relevant reference files

11. **Remind user about signatures**
    Remind that written resolutions require ALL directors' signatures

## Important Notes

- Written resolutions require **unanimous approval** of all directors
- No quorum issues since all directors participate
- Same legal effect as board meeting decision
- Must be signed by all directors

## Example

User: "Create a written resolution for granting options to new employees"
