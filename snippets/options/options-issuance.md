## Resolution {{N}}: Issuance of Options

### Background

The Board considered the issuance of options under the **{{PLAN_NAME}}** to {{RECIPIENT_DESCRIPTION}}.

<!-- Examples:
- "key employees and advisors"
- "the newly appointed Chief Technology Officer"
- "consultants providing strategic advisory services"
-->

### Legal Basis and Authorisation

This issuance is made pursuant to:
- The {{PLAN_NAME}} adopted by the General Meeting on {{PLAN_ADOPTION_DATE}}
- The authorisation granted to the Board by the General Meeting on {{AUTHORISATION_DATE}}, valid until {{AUTHORISATION_EXPIRY}}
- Chapter 10 of the Finnish Companies Act (osakeyhtiölaki 624/2006)

The Board confirmed that:
- The authorisation remains valid
- The issuance is within the maximum pool size approved by shareholders
- Sufficient options remain available under the plan

### Option Grants

The Board resolved to grant options as follows:

| Recipient | Role/Relationship | Number of Options | Exercise Price per Share | Vesting Commencement | Expiry Date |
|-----------|-------------------|-------------------|--------------------------|---------------------|-------------|
| {{RECIPIENT_1}} | {{ROLE_1}} | {{OPTIONS_1}} | EUR {{PRICE_1}} | {{VESTING_START_1}} | {{EXPIRY_1}} |
| {{RECIPIENT_2}} | {{ROLE_2}} | {{OPTIONS_2}} | EUR {{PRICE_2}} | {{VESTING_START_2}} | {{EXPIRY_2}} |
| **Total** | | **{{TOTAL_OPTIONS}}** | | | |

### Vesting Schedule

The options shall vest as follows:

{{VESTING_SCHEDULE}}

<!-- Examples:
- "4-year vesting with 1-year cliff: 25% vest on {{CLIFF_DATE}}, then 1/48 of the total grant vests monthly thereafter."
- "Monthly vesting over 3 years: 1/36 vests on the same day of each month starting from {{VESTING_START}}."
- "Performance-based: vests upon achievement of milestones as specified in the option agreement."
-->

Vesting is subject to the recipient's continued {{RELATIONSHIP}} with the company.

<!-- "employment" / "service relationship" / "consultancy agreement" -->

### Exercise Terms

- **Exercise price**: As specified in the table above, determined in accordance with the plan's pricing methodology
- **Exercise period**: Options may be exercised at any time after vesting until {{EXPIRY_DATE}}
- **Exercise method**: Written notice to the company with payment of exercise price
- **Payment**: Cash payment or {{CASHLESS_EXERCISE_NOTE}}

<!-- If cashless exercise permitted: "cashless exercise through net settlement (recipient receives shares equal to the intrinsic value)" -->

### Terms on Termination

In the event of termination of {{RELATIONSHIP}}:

{{TERMINATION_TERMS}}

<!-- Examples:
- "Good leaver (resignation, mutual termination): Vested options exercisable for 90 days; unvested options forfeit."
- "Bad leaver (termination for cause): All options (vested and unvested) forfeit immediately."
- "Death or disability: All unvested options vest immediately; estate/recipient has 12 months to exercise."
-->

### Shares upon Exercise

Upon exercise, the company shall issue ordinary shares with the following rights:
- Identical voting rights to existing ordinary shares
- Identical economic rights (dividends, liquidation proceeds)
- Dividend rights from date of registration in shareholder register
- Subject to any transfer restrictions in the Articles of Association
- Registration with PRH following issuance

### Dilution Update

The Board noted the following dilution impact:

| Metric | Before This Grant | After This Grant |
|--------|-------------------|------------------|
| Options granted under {{PLAN_NAME}} | {{OPTIONS_GRANTED_BEFORE}} | {{OPTIONS_GRANTED_AFTER}} |
| Options remaining in pool | {{OPTIONS_REMAINING_BEFORE}} | {{OPTIONS_REMAINING_AFTER}} |
| Current share capital | {{CURRENT_SHARES}} shares | {{CURRENT_SHARES}} shares |
| Fully diluted share capital | {{FD_SHARES_BEFORE}} shares | {{FD_SHARES_AFTER}} shares |
| Dilution from all options | {{DILUTION_BEFORE}}% | {{DILUTION_AFTER}}% |

### Option Agreements

The Board authorised {{AUTHORISED_SIGNATORY}} to execute option agreements with each recipient on behalf of the company, incorporating:
- The terms set out in this resolution
- The standard terms of the {{PLAN_NAME}}
- Any additional provisions required for tax efficiency or legal compliance

### Resolution

**The Board resolved to:**

1. **Grant** a total of {{TOTAL_OPTIONS}} options under the {{PLAN_NAME}} to the recipients specified above;
2. **Approve** the terms of the grants as set out in this resolution;
3. **Authorise** {{AUTHORISED_SIGNATORY}} to execute option agreements on behalf of the company; and
4. **Confirm** that this issuance is within the authorisation granted by the General Meeting and the maximum pool approved under the plan.

### Voting

{{VOTING_RECORD}}

<!-- Usually: "Approved unanimously." -->

{{RECUSAL_NOTE}}

<!-- If any director is a recipient: "{{DIRECTOR_NAME}} recused from voting on their own option grant." -->

### Follow-up Actions

- [ ] {{AUTHORISED_SIGNATORY}} to prepare and execute option agreements
- [ ] Recipients to receive and sign option agreements
- [ ] Update `/reference/option-plans.md` with new grants
- [ ] Maintain option grant register with vesting schedules
- [ ] Track vesting dates and exercise events

---

<!--
USAGE NOTES:

This snippet is for ISSUING options under an existing plan approved by shareholders.

Prerequisites:
- Option plan must be adopted by GM (use "option-plan-adoption.md" snippet)
- Valid authorisation to Board must exist (max 5 years per OYL 10:3)
- Sufficient options must remain in approved pool

Key legal requirements:
- Issuance must be within authorisation scope and timing
- Exercise price must not be below nominal value (if par value shares)
- Each recipient needs individual option agreement
- Shares issued upon exercise require PRH registration

Board discretion:
- Board decides WHO receives options (within eligible categories)
- Board decides HOW MANY options each person receives
- Board applies the pricing methodology from the plan
- Board sets vesting commencement date (typically grant date or employment start)

Common vesting structures in Finland:
- Tech companies: 4 years with 1-year cliff (Silicon Valley standard)
- Professional services: 3 years monthly
- Executive packages: Performance-based milestones

Tax considerations:
- Employee options: Taxable benefit when exercised (spread = FMV - exercise price)
- Non-employee options: Different tax treatment, consult tax advisor
- Exercise price at FMV minimizes immediate tax for employees

REMEMBER to:
- Update /reference/option-plans.md after each issuance
- Track remaining pool availability
- Check authorisation hasn't expired
- File with PRH when shares are issued upon exercise (not at grant)
- Maintain option holder register for cap table management
-->
