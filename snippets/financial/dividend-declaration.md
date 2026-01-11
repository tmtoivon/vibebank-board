## Resolution {{N}}: Declaration of Dividend

### Background

The {{DECISION_MAKER}} considered the distribution of profit for financial year {{FINANCIAL_YEAR}}.

### Legal Basis

This resolution is made pursuant to Chapter 13 of the Finnish Companies Act (osakeyhtiölaki 624/2006, "OYL"), which governs distribution of profit and return of capital.

### Distributable Equity

Based on the approved financial statements for FY {{FINANCIAL_YEAR}}, distributable equity is:

| Component | Amount (EUR) |
|-----------|--------------|
| Profit for FY {{FINANCIAL_YEAR}} | {{PROFIT_FY}} |
| Retained earnings from prior years | {{RETAINED_EARNINGS}} |
| Invested unrestricted equity fund (if any) | {{SVOP_AMOUNT}} |
| Less: Restricted amounts | ({{RESTRICTED}}) |
| **Total distributable equity** | **{{TOTAL_DISTRIBUTABLE}}** |

### Proposed Dividend

{{DIVIDEND_PROPOSAL_SOURCE}} proposed the following dividend distribution:

| Detail | Amount/Information |
|--------|-------------------|
| **Dividend per share** | EUR {{DIVIDEND_PER_SHARE}} |
| **Total number of shares** | {{TOTAL_SHARES}} shares |
| **Total dividend amount** | EUR {{TOTAL_DIVIDEND}} |
| **% of distributable equity** | {{PERCENTAGE_OF_DISTRIBUTABLE}}% |
| **Dividend yield** {{YIELD_NOTE}} | {{DIVIDEND_YIELD}}% |

<!-- Proposal source: "The Board of Directors" / "Shareholder {{NAME}}" -->
<!-- Yield note: "(based on {{VALUATION_BASIS}})" / "" -->

### Retained Earnings After Dividend

Following the dividend distribution, retained earnings will be:

| Item | Amount (EUR) |
|------|-------------|
| Distributable equity before dividend | {{DISTRIBUTABLE_BEFORE}} |
| Less: Dividend declared | ({{TOTAL_DIVIDEND}}) |
| **Retained in equity** | **{{RETAINED_AFTER}}** |

### Solvency Test (OYL 13:2)

The {{DECISION_MAKER}} confirmed that the dividend distribution satisfies the solvency test under OYL 13:2:

✓ **Liquidity test**: The company will be able to meet its debts as they fall due after the distribution
✓ **Balance sheet test**: The distribution does not exceed distributable equity
✓ **Prudent amount**: The distribution is prudent considering company's financial needs, growth plans, and risk profile

{{SOLVENCY_ASSESSMENT_DETAILS}}

### Payment Details

| Detail | Information |
|--------|-------------|
| **Record date** | {{RECORD_DATE}} |
| **Payment date** | {{PAYMENT_DATE}} |
| **Payment method** | {{PAYMENT_METHOD}} |

<!-- Payment method: "Bank transfer to shareholders' registered bank accounts" / "Cheque" / "As instructed by shareholders" -->

{{ENTITLEMENT_NOTE}}

<!-- "Shareholders registered in the shareholder register on the record date are entitled to the dividend." -->

### Tax Withholding

{{TAX_WITHHOLDING_INFO}}

<!-- Example:
"The company will withhold tax from dividend payments in accordance with Finnish tax law:
- Finnish resident individuals: {{TAX_RATE_1}}% withholding tax
- Finnish resident companies: No withholding (dividend generally tax-exempt)
- Non-resident shareholders: {{TAX_RATE_2}}% withholding tax (subject to applicable tax treaty)

Shareholders are responsible for reporting dividends in their tax returns. The company will provide dividend statements for tax purposes."
-->

### Impact on Equity

The dividend will be recorded as follows in the company's accounts:

```
Dr Retained Earnings  EUR {{TOTAL_DIVIDEND}}
   Cr Dividend Payable               EUR {{TOTAL_DIVIDEND}}

(Upon payment:)
Dr Dividend Payable   EUR {{TOTAL_DIVIDEND}}
   Cr Cash                           EUR {{TOTAL_DIVIDEND}}
```

### Board Assessment

{{BOARD_ASSESSMENT}}

<!-- Example:
"The Board assessed that the proposed dividend:
- Is within the company's financial capacity
- Does not jeopardize the company's solvency or liquidity
- Leaves adequate reserves for working capital (EUR {{WC_RESERVE}})
- Supports the company's growth plans for {{NEXT_YEAR}}
- Is consistent with the company's dividend policy of {{POLICY}}
- Provides reasonable return to shareholders ({{RETURN}}% of equity)

The Board recommends approval of the dividend."
-->

### Resolution

**The {{DECISION_MAKER}} resolved to:**

1. **Approve** a dividend distribution of EUR {{DIVIDEND_PER_SHARE}} per share, totaling EUR {{TOTAL_DIVIDEND}};
2. **Confirm** that the solvency test under OYL 13:2 is satisfied;
3. **Determine** that the record date is {{RECORD_DATE}} and payment date is {{PAYMENT_DATE}};
4. **Retain** EUR {{RETAINED_AFTER}} in equity;
5. **Authorise** {{AUTHORISED_PERSON}} to arrange payment of the dividend and withholding of taxes; and
6. **Note** that shareholders registered on {{RECORD_DATE}} are entitled to the dividend.

### Voting

{{VOTING_RECORD}}

### Follow-up Actions

- [ ] Record dividend liability in accounts
- [ ] Prepare shareholder list as of record date ({{RECORD_DATE}})
- [ ] Calculate tax withholding for each shareholder
- [ ] Arrange payment on {{PAYMENT_DATE}}
- [ ] Provide dividend statements to shareholders for tax reporting
- [ ] Update `/reference/share-capital.md` with post-dividend equity
- [ ] File required tax reports with Finnish Tax Administration

---

<!--
USAGE NOTES:

Distributable equity (OYL 13:1):
- Unrestricted equity shown in latest approved financial statements
- Includes: profit for year, retained earnings, unrestricted reserves (SVOP)
- Excludes: share capital, legal reserves, restricted amounts

Solvency test (OYL 13:2):
- Distribution must not endanger company's ability to pay debts
- Board must assess: liquidity, balance sheet strength, future needs
- Violating solvency test = Board/shareholder personally liable

Record and payment dates:
- Record date: Shareholders on this date receive dividend
- Payment date: When dividend actually paid (typically 1-4 weeks after record)
- AGM sets both dates

Tax treatment:
- Individuals: 25-55% income tax on net dividend (85% taxable if listed, 75% if unlisted)
- Companies: Generally tax-exempt (certain conditions)
- Withholding tax: Required for non-residents

REMEMBER to update equity in reference files and arrange timely payment.
-->
