## Resolution {{N}}: {{ACTION}} of Auditor

<!-- ACTION: "Appointment" / "Re-appointment" / "Change" -->

### Background

The {{DECISION_MAKER}} considered the {{AUDITOR_MATTER}}.

<!-- Examples:
- "appointment of an auditor for the company"
- "re-appointment of the current auditor"
- "change of auditor"
- "waiver of audit requirement"
-->

### Legal Basis

OYL 6:1 provides that a company must have one auditor (or audit firm), unless the audit requirement is waived under OYL 6:2.

### Audit Requirement Assessment

{{AUDIT_REQUIREMENT_STATUS}}

<!-- For companies with mandatory audit:
"The company {{EXCEEDS_CRITERIA}} and therefore must have an auditor per OYL 6:1."

For companies eligible to waive:
"Under OYL 6:2, a company may waive the audit requirement if no more than ONE of the following criteria was exceeded in the financial year just ended AND the preceding financial year:
- Balance sheet total: EUR 350,000
- Revenue: EUR 700,000
- Employees (average): 10 persons

The company's figures:
| Criterion | {{PRIOR_YEAR}} | {{CURRENT_YEAR}} | Criteria Exceeded |
|-----------|----------------|------------------|-------------------|
| Balance sheet | EUR {{BS_PY}} | EUR {{BS_CY}} | {{BS_EXCEEDED}} |
| Revenue | EUR {{REV_PY}} | EUR {{REV_CY}} | {{REV_EXCEEDED}} |
| Employees | {{EMP_PY}} | {{EMP_CY}} | {{EMP_EXCEEDED}} |

**Criteria exceeded**: {{TOTAL_EXCEEDED}}

{{AUDIT_CONCLUSION}}"

Conclusion examples:
- "The company MUST have an auditor (2+ criteria exceeded)."
- "The company MAY waive audit requirement (0-1 criteria exceeded)."
-->

### {{RESOLUTION_TYPE}}

<!-- Use one of the following sections based on decision -->

#### A. Appointment of Auditor

The {{DECISION_MAKER}} resolved to appoint {{AUDITOR_NAME}} as the company's auditor.

**Auditor details:**
- **Name**: {{AUDITOR_FULL_NAME}}
- **Firm**: {{AUDIT_FIRM}}
- **Credentials**: {{CREDENTIALS}}
- **Principal auditor**: {{PRINCIPAL_AUDITOR}} (if audit firm)
- **Term**: {{TERM}}

<!-- Credentials: "KHT" (Authorized Public Accountant) / "HTM" (Qualified Public Accountant) -->
<!-- Term: "Until the end of the next AGM" (standard) -->

{{AUDITOR_BACKGROUND}}

#### B. Waiver of Audit Requirement (if applicable)

The {{DECISION_MAKER}} resolved to waive the audit requirement under OYL 6:2.

**Consequences of waiving audit:**
- The company will not have an auditor
- Financial statements will not be audited
- OYL 6:4 requires minimum **3 directors** (instead of 1)
- Some stakeholders (banks, investors) may require audited statements

**Board composition check:**
{{BOARD_SIZE_CONFIRMATION}}

<!-- "✓ The Board currently has {{N}} members, satisfying the requirement of 3+ directors."
     "✗ The Board currently has {{N}} members. An additional director must be appointed to meet the 3-member requirement." -->

### Auditor Remuneration

{{REMUNERATION_DECISION}}

<!-- Options:
- "The auditor's remuneration shall be paid according to approved invoice."
- "The auditor's remuneration is set at EUR {{AMOUNT}} per annum."
- "The auditor's remuneration shall be EUR {{AMOUNT}} for the audit plus reasonable expenses."
-->

### PRH Filing

The {{DECISION_MAKER}} noted that this {{ACTION_TYPE}} must be filed with PRH within 2 months.

### Resolution

**The {{DECISION_MAKER}} resolved to:**

{{MAIN_RESOLUTION}}

<!-- For appointment:
"1. **Appoint** {{AUDITOR_NAME}}, {{CREDENTIALS}}, {{FIRM}}, as the company's auditor;
2. **Determine** that the auditor's remuneration shall be {{REMUNERATION}};
3. **Note** that the auditor's term runs until the end of the next AGM; and
4. **Instruct** the company secretary to file notification with PRH within 2 months."

For waiver:
"1. **Waive** the audit requirement pursuant to OYL 6:2;
2. **Confirm** that the Board consists of {{N}} members, meeting the requirement of 3+ directors;
3. **Note** that financial statements will not be audited; and
4. **Instruct** the company secretary to file notification with PRH within 2 months."
-->

### Voting

{{VOTING_RECORD}}

### Follow-up Actions

**For auditor appointment:**
- [ ] File YTJ2 notification with PRH within 2 months
- [ ] Execute auditor engagement letter
- [ ] Provide auditor with access to company records and systems
- [ ] Schedule audit timetable for FY {{YEAR}}
- [ ] Update `/reference/directors-register.md` with auditor information

**For audit waiver:**
- [ ] File YTJ2 notification with PRH within 2 months
- [ ] Confirm Board has 3+ directors (appoint additional if needed)
- [ ] Notify banks and other stakeholders
- [ ] Update company governance documents

---

<!--
USAGE NOTES:

Audit requirement (OYL 6:1-2):
- Default: All companies must have auditor
- Exception: Can waive if small (OYL 6:2 criteria)
- If waived: Must have 3+ directors

Waiver criteria (OYL 6:2):
NO MORE THAN ONE of these exceeded in current AND prior FY:
- Balance sheet EUR 350,000
- Revenue EUR 700,000
- Employees 10

Auditor qualifications:
- KHT (Authorized Public Accountant) or HTM (Qualified)
- Must be independent
- Can be individual or firm

Auditor duties:
- Audit financial statements
- Issue auditor's report
- Report to shareholders at AGM
- Report to Board if material issues

Auditor appointment:
- By General Meeting (typically at AGM)
- Term until next AGM
- Can be re-appointed unlimited times

Changing auditor:
- GM can change at any time
- Should notify current auditor
- Consider transition period

REMEMBER to file with PRH and confirm board size if waiving audit.
-->
