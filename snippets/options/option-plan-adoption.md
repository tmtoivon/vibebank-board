## Resolution {{N}}: Adoption of Option Plan

### Background

The {{PROPOSER}} presented a proposal to establish an option plan for {{PURPOSE}}.

<!-- Common purposes:
- "incentivising and retaining key employees and advisors"
- "aligning management interests with shareholder value creation"
- "attracting and retaining talented personnel"
-->

### Legal Basis

The adoption of an option plan is governed by Chapter 10 of the Finnish Companies Act (osakeyhtiölaki 624/2006, "OYL"), which regulates the issuance of equity-related rights including options (optio-oikeudet).

### Option Plan Terms

The meeting considered the following key terms of the **{{PLAN_NAME}}**:

| Parameter | Details |
|-----------|---------|
| **Plan name** | {{PLAN_NAME}} |
| **Maximum pool size** | {{MAX_OPTIONS}} options |
| **Underlying shares** | {{MAX_SHARES}} ordinary shares (representing approximately {{DILUTION_PERCENTAGE}}% dilution on a fully diluted basis) |
| **Exercise price** | {{EXERCISE_PRICE_METHOD}} |
| **Vesting schedule** | {{VESTING_TERMS}} |
| **Exercise period** | {{EXERCISE_PERIOD}} |
| **Expiry** | {{EXPIRY_DATE}} |
| **Transferability** | {{TRANSFERABILITY}} |
| **Treatment on termination** | {{TERMINATION_TREATMENT}} |

### Exercise Price Methodology

{{EXERCISE_PRICE_DETAILS}}

<!-- Examples:
- "EUR {{AMOUNT}} per share, being the fair market value determined by the Board based on the most recent funding round valuation."
- "The lower of (i) EUR {{AMOUNT}} per share or (ii) the price per share in the next equity financing round."
- "EUR {{AMOUNT}} per share, determined by an independent valuation dated {{VALUATION_DATE}}."
-->

### Vesting Terms

{{VESTING_DETAILS}}

<!-- Examples:
- "4-year vesting with 1-year cliff: 25% vest after 12 months, remainder vests monthly over following 36 months."
- "3-year monthly vesting: 1/36 vests each month from grant date."
- "Performance-based vesting subject to achievement of milestones approved by the Board."
-->

### Share Issuance upon Exercise

Shares issued upon exercise of options shall:
- Be ordinary shares with identical rights to existing ordinary shares
- Be registered in the shareholder register
- Carry dividend rights from the date of registration
- Be subject to any transfer restrictions in the Articles of Association

### Authorisation to Board

The meeting resolved to authorise the Board of Directors to:
- Issue options under the plan to employees, directors, advisors and consultants
- Determine individual allocations within the pool
- Approve option agreements on terms consistent with the plan
- Make technical amendments to the plan that do not materially change its terms

This authorisation is valid for **{{AUTHORISATION_PERIOD}}** from the date of this resolution.

<!-- Maximum 5 years per OYL 10:3 -->

### Dilution Impact

The Board noted that:
- Maximum dilution if all options are granted and exercised: {{DILUTION_PERCENTAGE}}%
- Current share capital: {{CURRENT_SHARES}} shares
- Share capital after full dilution: {{FULLY_DILUTED_SHARES}} shares

### Resolution

**The meeting resolved to:**

1. **Adopt** the {{PLAN_NAME}} on the terms presented;
2. **Approve** the issuance of up to {{MAX_OPTIONS}} options convertible into up to {{MAX_SHARES}} ordinary shares;
3. **Authorise** the Board of Directors to issue options under the plan and approve individual allocations, with such authorisation valid for {{AUTHORISATION_PERIOD}} from the date of this resolution; and
4. **Note** that shares issued upon exercise of options will be ordinary shares with identical rights to existing ordinary shares.

### Voting

{{VOTING_RECORD}}

<!-- Examples:
- "Approved unanimously."
- "Approved by {{VOTES_FOR}} votes in favour, {{VOTES_AGAINST}} against, {{ABSTENTIONS}} abstentions."
- "Approved by shareholders holding {{PERCENTAGE}}% of shares represented."
-->

### Follow-up Actions

- [ ] Board to prepare detailed option agreement template
- [ ] Board to approve individual option grants under authorisation
- [ ] Update `/reference/option-plans.md` with new plan details
- [ ] Maintain register of option grants under this plan

---

<!--
USAGE NOTES:

This snippet is for ADOPTING a new option plan at a General Meeting (AGM or EGM).

After adoption, the Board can issue options under the plan using the "options-issuance.md" snippet.

Key legal requirements:
- Option plan must be approved by General Meeting (OYL 10:1)
- GM can delegate authority to Board to issue options (max 5 years per OYL 10:3)
- Exercise price must not be below nominal value (if par value shares)
- Dilution impact should be disclosed to shareholders

Common practice:
- Tech/growth companies often use 4-year vesting with 1-year cliff
- Exercise price typically set at fair market value at grant date
- Maximum pool often 10-15% of fully diluted share capital
- Option agreements are individual contracts with each recipient

REMEMBER to:
- Update /reference/option-plans.md after adoption
- Track total pool size and allocations
- Note authorisation expiry date (max 5 years)
- Consider tax treatment for recipients (employee vs consultant options)
-->
