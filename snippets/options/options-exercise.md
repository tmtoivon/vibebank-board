## Resolution {{N}}: Exercise of Options and Share Issuance

### Background

The Board noted that {{OPTION_HOLDER}} has delivered an exercise notice for options granted under the **{{PLAN_NAME}}**.

### Exercise Notice Details

| Parameter | Details |
|-----------|---------|
| **Option holder** | {{OPTION_HOLDER}} |
| **Original grant date** | {{GRANT_DATE}} |
| **Number of options granted** | {{TOTAL_GRANTED}} |
| **Number of options vested** | {{VESTED_OPTIONS}} |
| **Number of options being exercised** | {{EXERCISED_OPTIONS}} |
| **Exercise price per share** | EUR {{EXERCISE_PRICE}} |
| **Total exercise payment** | EUR {{TOTAL_PAYMENT}} |
| **Exercise date** | {{EXERCISE_DATE}} |

### Verification of Exercise Right

The Board confirmed that:
- The options being exercised have fully vested in accordance with the vesting schedule
- The exercise is within the permitted exercise period (options expire on {{EXPIRY_DATE}})
- The option holder has {{RELATIONSHIP_STATUS}} with the company
- {{EXERCISE_CONDITIONS_MET}}

<!-- Examples of conditions met:
- "No termination events have occurred that would cause forfeiture"
- "The option holder remains an active employee in good standing"
- "All conditions precedent to exercise have been satisfied"
-->

### Payment Verification

The Board confirmed receipt of payment for the exercise:

{{PAYMENT_METHOD}}

<!-- Examples:
- "Cash payment of EUR {{TOTAL_PAYMENT}} received via bank transfer on {{PAYMENT_DATE}}."
- "Cashless exercise via net settlement: the option holder shall receive {{NET_SHARES}} shares representing the intrinsic value, and {{WITHHELD_SHARES}} shares withheld to cover the exercise price."
- "Payment by promissory note in the amount of EUR {{TOTAL_PAYMENT}}, due {{DUE_DATE}}."
-->

### Share Issuance

The Board resolved to issue **{{EXERCISED_OPTIONS}} ordinary shares** to {{OPTION_HOLDER}} upon exercise of the options.

The shares shall have the following rights:
- **Share class**: Ordinary shares
- **Voting rights**: One vote per share
- **Economic rights**: Identical to existing ordinary shares
- **Dividend rights**: From date of registration in shareholder register ({{REGISTRATION_DATE}})
- **Transfer restrictions**: Subject to any restrictions in the Articles of Association
- **Listing**: {{LISTING_STATUS}}

<!-- "The company's shares are not listed" / "The shares are not currently admitted to trading" -->

### Updated Share Capital

Following this exercise, the company's share capital is as follows:

| Metric | Before Exercise | After Exercise | Change |
|--------|----------------|----------------|---------|
| Number of shares | {{SHARES_BEFORE}} | {{SHARES_AFTER}} | +{{EXERCISED_OPTIONS}} |
| {{SHARE_CAPITAL_METRIC}} | {{CAPITAL_BEFORE}} | {{CAPITAL_AFTER}} | {{CAPITAL_CHANGE}} |

<!-- For par value shares: "Share capital (EUR)" / For no par value: leave this row or note "No par value shares" -->

### Updated Option Plan Status

The Board noted the updated status of the {{PLAN_NAME}}:

| Metric | Status |
|--------|--------|
| Options granted to date | {{TOTAL_GRANTED_ALL}} |
| Options exercised to date | {{TOTAL_EXERCISED}} |
| Options forfeited/expired | {{TOTAL_FORFEITED}} |
| Options outstanding (unvested + vested) | {{TOTAL_OUTSTANDING}} |
| Options remaining in pool | {{REMAINING_POOL}} |

### PRH Filing

The Board noted that this share issuance {{PRH_FILING_REQUIREMENT}}.

<!-- Examples:
- "must be filed with the Finnish Patent and Registration Office (PRH) within 2 months"
- "does not require separate PRH filing as it falls under the share capital increase already registered on {{DATE}}"
- "will be included in the next periodic filing to PRH"
-->

### Shareholder Register

The Board instructed the company secretary to:
- Update the shareholder register to reflect {{OPTION_HOLDER}}'s ownership of {{EXERCISED_OPTIONS}} shares
- Issue share certificate(s) to {{OPTION_HOLDER}} if requested
- Notify PRH of the updated shareholder information {{IF_REQUIRED}}
- Update the cap table and option tracking spreadsheet

### Resolution

**The Board resolved to:**

1. **Approve** the exercise of {{EXERCISED_OPTIONS}} options by {{OPTION_HOLDER}};
2. **Confirm** receipt of payment of EUR {{TOTAL_PAYMENT}};
3. **Issue** {{EXERCISED_OPTIONS}} ordinary shares to {{OPTION_HOLDER}};
4. **Instruct** the company secretary to update the shareholder register and file with PRH as required; and
5. **Note** that {{REMAINING_OPTIONS}} options granted to {{OPTION_HOLDER}} remain outstanding ({{VESTED_REMAINING}} vested, {{UNVESTED_REMAINING}} unvested).

### Voting

{{VOTING_RECORD}}

<!-- Usually: "Approved unanimously." -->

### Follow-up Actions

- [ ] Update shareholder register with new shares
- [ ] {{PRH_FILING_ACTION}}
- [ ] Issue share certificate to {{OPTION_HOLDER}} if requested
- [ ] Update `/reference/share-capital.md` with new share count
- [ ] Update `/reference/option-plans.md` with exercise record
- [ ] Provide tax documentation to {{OPTION_HOLDER}} for taxable benefit reporting
- [ ] Update cap table and dilution calculations

---

<!--
USAGE NOTES:

This snippet is for APPROVING the exercise of options and issuing shares.

Prerequisites:
- Options must be granted under an approved plan
- Options must be vested
- Option holder must be within exercise period
- Payment must be received (or cashless exercise approved)

Key legal requirements:
- Board must verify exercise is valid per option agreement terms
- Payment must be received before share issuance (unless cashless)
- Shares issued must match underlying share class from option plan
- PRH filing required if changes share capital or shareholder composition

Exercise methods:
1. Cash exercise: Holder pays exercise price × number of shares
2. Cashless (net settlement): Holder receives shares equal to intrinsic value only
3. Promissory note: Holder gives note for exercise price (must be permitted)

Tax implications:
- For employees: Taxable benefit = (FMV at exercise - exercise price) × shares
- Company may have withholding obligations
- Option holder responsible for tax unless company withholds

PRH filing:
- Required for share capital changes (if par value shares)
- May be required for significant shareholder changes
- Deadline: Generally within 2 months of share issuance
- Supporting docs: Board resolution, shareholder register update

Post-exercise option status:
- Exercised options are cancelled
- Remaining vested options can still be exercised
- Unvested options continue vesting per schedule (if holder remains employed/engaged)

REMEMBER to:
- Update /reference/share-capital.md with new share count
- Update /reference/option-plans.md to record exercise
- Track remaining vested/unvested options for the holder
- File with PRH if required
- Provide tax documentation to option holder
- Update cap table for dilution tracking
-->
