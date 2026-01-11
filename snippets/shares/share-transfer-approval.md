## Resolution {{N}}: Approval of Share Transfer

### Background

The Board considered a request for approval of a transfer of shares in the company from {{SELLER}} to {{BUYER}}.

### Legal Basis and Transfer Restrictions

{{TRANSFER_RESTRICTION_SOURCE}}

<!-- Examples:
- "The company's Articles of Association (§{{SECTION}}) provide that share transfers require prior approval of the Board of Directors."
- "The Shareholders' Agreement dated {{DATE}} requires board approval for transfers to third parties."
- "As a private limited company (Oy), the Articles impose transfer restrictions in accordance with OYL 3:6."
-->

### Transfer Details

| Parameter | Details |
|-----------|---------|
| **Seller** | {{SELLER_NAME}} |
| **Current shareholding** | {{SELLER_CURRENT_SHARES}} shares ({{SELLER_PERCENTAGE}}%) |
| **Buyer** | {{BUYER_NAME}} |
| **Number of shares to be transferred** | {{SHARES_TO_TRANSFER}} shares |
| **Transfer price** | EUR {{TRANSFER_PRICE}} per share (total: EUR {{TOTAL_CONSIDERATION}}) |
| **Seller's remaining shares** | {{SELLER_REMAINING_SHARES}} shares ({{SELLER_REMAINING_PERCENTAGE}}%) |
| **Buyer's total shareholding after transfer** | {{BUYER_TOTAL_AFTER}} shares ({{BUYER_PERCENTAGE_AFTER}}%) |
| **Transfer date** | {{TRANSFER_DATE}} |

### Buyer Information

{{BUYER_DETAILS}}

<!-- Provide relevant information:
- "{{BUYER_NAME}} is {{DESCRIPTION}} (e.g., an existing shareholder, a new investor, a family member of the seller)."
- "{{BUYER_NAME}}, born {{DOB}}, is {{RELATIONSHIP_TO_COMPANY}}."
- "{{BUYER_NAME}} is a company registered in {{JURISDICTION}} with business ID {{ID}}."
-->

### Transfer Rationale

{{TRANSFER_RATIONALE}}

<!-- Examples:
- "The transfer is part of estate planning arrangements by {{SELLER}}."
- "The buyer is a new strategic investor who will contribute {{VALUE}} to the company."
- "This is a transfer between family members of {{FAMILY}}."
- "The transfer results from {{SELLER}}'s departure from the company."
-->

### Pre-emption Rights

The Board noted that {{PREEMPTION_STATUS}}.

<!-- Options:
- "shareholders' pre-emption rights (etuoikeus) have been waived or the offer period has expired without any shareholder exercising their right to purchase the shares"
- "the transfer is exempt from pre-emption rights under the Shareholders' Agreement because {{REASON}}"
- "pre-emption rights were offered to existing shareholders on {{DATE}} and no shareholder elected to purchase the shares"
- "no pre-emption rights apply to this transfer per the Articles of Association"
-->

{{PREEMPTION_DETAILS}}

<!-- If pre-emption was offered:
"Pre-emption rights were offered to the following shareholders on {{OFFER_DATE}}:
- {{SHAREHOLDER_1}}: Offered {{SHARES_1}} shares at EUR {{PRICE}} per share
- {{SHAREHOLDER_2}}: Offered {{SHARES_2}} shares at EUR {{PRICE}} per share

The offer period expired on {{EXPIRY_DATE}} without any acceptances."
-->

### Board Considerations

The Board considered the following factors:

{{BOARD_CONSIDERATIONS}}

<!-- Examples:
1. "The buyer has sufficient financial capacity to complete the purchase."
2. "The buyer is willing to execute the Shareholders' Agreement."
3. "The transfer price reflects fair market value."
4. "The transfer will not adversely affect the company's operations or governance."
5. "{{BUYER}} has relevant industry experience that may benefit the company."
6. "The transfer complies with the requirements of the Articles of Association and Shareholders' Agreement."
-->

### Conditions of Approval

The Board's approval is subject to the following conditions:

{{CONDITIONS}}

<!-- Common conditions:
1. "{{BUYER}} executes a deed of adherence to the Shareholders' Agreement dated {{DATE}}."
2. "Payment of the transfer price is completed by {{PAYMENT_DEADLINE}}."
3. "{{BUYER}} provides satisfactory identification documents to the company."
4. "Any required regulatory approvals or third-party consents are obtained."
5. "{{SELLER}} confirms there are no pledges or encumbrances over the shares."
-->

### Shareholders' Agreement

{{SHA_STATUS}}

<!-- Options:
- "{{BUYER}} shall execute a deed of adherence to the Shareholders' Agreement dated {{SHA_DATE}}, becoming bound by all its terms as if an original party."
- "The existing Shareholders' Agreement dated {{SHA_DATE}} shall be amended to include {{BUYER}} as a party."
- "No Shareholders' Agreement is in place; this approval is solely under the Articles of Association."
-->

### Updated Shareholding Structure

Following this transfer, the shareholding structure will be:

| Shareholder | Shares Before | Shares After | % Before | % After | Change |
|-------------|---------------|--------------|----------|---------|--------|
| {{SHAREHOLDER_1}} | {{S1_BEFORE}} | {{S1_AFTER}} | {{S1_PCT_BEFORE}}% | {{S1_PCT_AFTER}}% | {{S1_CHANGE}} |
| {{SHAREHOLDER_2}} | {{S2_BEFORE}} | {{S2_AFTER}} | {{S2_PCT_BEFORE}}% | {{S2_PCT_AFTER}}% | {{S2_CHANGE}} |
| {{BUYER_NAME}} | {{B_BEFORE}} | {{B_AFTER}} | {{B_PCT_BEFORE}}% | {{B_PCT_AFTER}}% | +{{SHARES_TO_TRANSFER}} |
| **Total** | **{{TOTAL_SHARES}}** | **{{TOTAL_SHARES}}** | **100%** | **100%** | |

### PRH Notification

{{PRH_REQUIREMENT}}

<!-- Options:
- "The Board noted that this transfer must be notified to PRH if {{BUYER}} becomes a significant shareholder (≥{{THRESHOLD}}%)."
- "No PRH filing is required for this transfer as it does not change the company structure."
- "The Board instructed the company secretary to update the shareholder register maintained at the company."
-->

### Resolution

**The Board resolved to:**

1. **Approve** the transfer of {{SHARES_TO_TRANSFER}} shares from {{SELLER}} to {{BUYER}};
2. **Confirm** that all pre-emption rights (if applicable) have been satisfied or waived;
3. **Require** that the conditions specified above be satisfied prior to registration of the transfer;
4. **Authorise** {{AUTHORISED_PERSON}} to execute any documents necessary to effect the transfer, including share transfer forms and deeds of adherence; and
5. **Instruct** the company secretary to update the shareholder register upon completion of the transfer and satisfaction of all conditions.

### Voting

{{VOTING_RECORD}}

<!-- Usually: "Approved unanimously."
     Note any recusals: "{{DIRECTOR}} recused from voting due to {{CONFLICT}}." -->

### Follow-up Actions

- [ ] {{BUYER}} to execute deed of adherence to Shareholders' Agreement
- [ ] Transfer payment to be completed by {{PAYMENT_DEADLINE}}
- [ ] {{AUTHORISED_PERSON}} to execute share transfer documentation
- [ ] Update shareholder register
- [ ] {{PRH_FILING_ACTION}}
- [ ] Update `/reference/share-capital.md` with new ownership structure
- [ ] Update cap table
- [ ] Provide updated shareholder list to auditor if required

---

<!--
USAGE NOTES:

This snippet is for BOARD APPROVAL of share transfers where Articles of Association or SHA require consent.

Legal framework:

Transfer restrictions in Oy (OYL 3:6):
- Private companies (Oy) commonly restrict share transfers in Articles
- Typical restriction: "Share transfers require prior board approval"
- Purpose: Maintain control over shareholder composition

Common transfer restriction types:
1. Board consent: Board must approve transfer
2. Pre-emption rights: Existing shareholders have right of first refusal
3. Prohibited transfers: Transfers to competitors, certain persons prohibited
4. Permitted transfers: Family transfers, inheritance often exempt

Pre-emption rights (etuoikeus):
- Shareholders have right to purchase before transfer to third party
- Usually pro rata to existing shareholdings
- Price and terms match third-party offer
- Time-limited (e.g., 30 days to accept)

Board's discretion:
- Articles may give board absolute discretion to refuse
- Articles may specify objective criteria (e.g., "not a competitor")
- Board should act reasonably and in company's interests
- Unreasonable refusal may be challenged

Shareholders' Agreement implications:
- SHA often contains additional transfer restrictions
- Buyer must typically adhere to SHA terms
- "Drag-along" and "tag-along" rights may apply
- Violation of SHA transfer restrictions can void transfer

Transfer mechanics:
1. Seller notifies board and shareholders of proposed transfer
2. Pre-emption rights offered (if applicable)
3. If not exercised, board considers approval
4. Board approves (with/without conditions)
5. Conditions satisfied
6. Share transfer form signed by seller and buyer
7. Shareholder register updated
8. PRH notified if required

PRH notification:
- Not always required for transfers (no change to share capital)
- May be required if beneficial ownership changes significantly
- Required if new shareholder crosses reporting threshold
- Good practice: Maintain updated shareholder register at company

Common approval conditions:
- Execution of SHA deed of adherence
- Payment of transfer price
- Provision of ID documents
- Regulatory approvals (if applicable, e.g., competition, foreign investment)
- No pledges or encumbrances on shares

Grounds for refusing approval (if Articles permit):
- Buyer is competitor or otherwise harmful to company
- Buyer has insufficient financial capacity
- Buyer refuses to sign SHA
- Transfer would trigger unwanted regulatory consequences
- Transfer would disrupt cap table for future fundraising

REMEMBER to:
- Check Articles for specific approval requirements
- Verify pre-emption rights have been properly offered and expired
- Update shareholder register after transfer completed
- Update /reference/share-capital.md with new ownership
- Ensure SHA deed of adherence executed by buyer
- Consider drag-along/tag-along implications
- Update cap table
-->
