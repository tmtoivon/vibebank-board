## Resolution {{N}}: Approval of Loan

### Background

The Board considered {{LOAN_PROPOSAL}}.

<!-- Examples:
- "a proposal to borrow EUR {{AMOUNT}} from {{LENDER}} to finance {{PURPOSE}}"
- "the terms of a proposed loan facility from {{LENDER}}"
- "refinancing of existing debt with {{NEW_LENDER}}"
-->

### Loan Details

| Parameter | Details |
|-----------|---------|
| **Lender** | {{LENDER_NAME}} |
| **Loan type** | {{LOAN_TYPE}} |
| **Principal amount** | EUR {{PRINCIPAL}} |
| **Interest rate** | {{INTEREST_RATE}}% per annum {{INTEREST_TYPE}} |
| **Fees** | {{FEES}} |
| **Drawdown date** | {{DRAWDOWN_DATE}} |
| **Maturity date** | {{MATURITY_DATE}} |
| **Repayment schedule** | {{REPAYMENT_SCHEDULE}} |
| **Security** | {{SECURITY}} |
| **Guarantees** | {{GUARANTEES}} |
| **Covenants** | {{COVENANTS}} |

<!-- Loan types: "Term loan" / "Revolving credit facility" / "Overdraft facility" / "Bridge loan" / "Invoice financing" -->
<!-- Interest type: "(fixed)" / "(variable, linked to {{BENCHMARK}})" / "({{BASE}} + {{MARGIN}} margin)" -->
<!-- Security: "Unsecured" / "Secured by {{COLLATERAL}}" -->

### Purpose of Loan

{{PURPOSE_DESCRIPTION}}

<!-- Examples:
- "The loan proceeds will be used for {{PURPOSE}}."
- "Use of proceeds:
  - EUR {{AMOUNT_1}} for {{PURPOSE_1}}
  - EUR {{AMOUNT_2}} for {{PURPOSE_2}}
  - EUR {{AMOUNT_3}} for general working capital"
-->

### Loan Terms Summary

#### Interest and Fees

{{INTEREST_DETAILS}}

<!-- Example:
"- **Interest rate**: {{RATE}}% per annum ({{FIXED/VARIABLE}})
- **Interest calculation**: {{METHOD}} (e.g., 30/360, actual/365)
- **Interest payment**: {{FREQUENCY}} (e.g., quarterly in arrears)
- **Arrangement fee**: EUR {{FEE}} ({{PERCENTAGE}}% of principal)
- **Commitment fee**: {{COMMITMENT_FEE}} (if revolving facility)
- **Early repayment fee**: {{EARLY_REPAYMENT_FEE}}"
-->

#### Repayment

{{REPAYMENT_DETAILS}}

<!-- Examples:
- "Bullet repayment: Full principal due on {{MATURITY_DATE}}"
- "Amortizing: EUR {{AMOUNT}} quarterly, with final payment of EUR {{FINAL}} on {{MATURITY_DATE}}"
- "Interest-only until {{DATE}}, then {{REPAYMENT_STRUCTURE}}"
- "Revolving facility: Principal repayable on demand / at maturity"
-->

#### Security and Guarantees

{{SECURITY_DETAILS}}

<!-- If secured:
"The loan is secured by:
1. {{SECURITY_1}} (e.g., "First-ranking pledge over {{ASSETS}}")
2. {{SECURITY_2}} (e.g., "Floating charge over inventory and receivables")
3. {{SECURITY_3}}

The Board resolved to grant the security interests specified above."

If unsecured:
"The loan is unsecured. No collateral or security interests will be granted."

Guarantees:
"{{GUARANTOR_1}} has agreed to guarantee the loan up to EUR {{GUARANTEE_AMOUNT_1}}.
{{GUARANTOR_2}} has agreed to guarantee the loan up to EUR {{GUARANTEE_AMOUNT_2}}."
-->

#### Financial Covenants

{{COVENANTS_DETAILS}}

<!-- If applicable:
"The loan agreement includes the following financial covenants, to be tested {{TESTING_FREQUENCY}}:

1. **Minimum equity ratio**: ≥ {{RATIO}}%
2. **Maximum leverage ratio** (Net Debt / EBITDA): ≤ {{RATIO}}x
3. **Minimum liquidity**: EUR {{AMOUNT}} cash and equivalents
4. **Debt service coverage ratio**: ≥ {{RATIO}}x

Breach of covenants may result in {{CONSEQUENCES}}."

If none:
"The loan agreement does not contain financial covenants."
-->

#### Other Covenants and Conditions

{{OTHER_COVENANTS}}

<!-- Examples of typical covenants:
"- **Negative pledge**: No additional security interests without lender consent
- **Restrictions on dividends**: Dividends limited to {{LIMIT}} or require lender consent
- **Change of control**: Loan becomes due upon change of majority ownership
- **Mandatory prepayment**: Upon {{EVENTS}} (e.g., asset sales, equity issuances)
- **Use of proceeds**: Proceeds used only for specified purposes
- **Financial reporting**: Quarterly financial statements to lender
- **Information rights**: Lender may inspect books and records"
-->

#### Conditions Precedent to Drawdown

{{CONDITIONS_PRECEDENT}}

<!-- Example:
"The loan is subject to the following conditions precedent to be satisfied before drawdown:
1. Execution of loan agreement
2. {{SECURITY_DOCUMENTS_EXECUTED}}
3. Legal opinions delivered by company's counsel
4. No material adverse change since application
5. {{COMPANY_CERTIFICATES}}
6. {{OTHER_CONDITIONS}}"
-->

### Board Assessment

The Board assessed that:

{{BOARD_ASSESSMENT}}

<!-- Example:
"1. **Need**: The loan is necessary to {{REASON}}.
2. **Terms**: The loan terms (interest rate {{RATE}}%, fees {{FEES}}, maturity {{TERM}}) are reasonable and competitive.
3. **Affordability**: The company can service the debt based on projected cash flows.
4. **Alternatives**: Alternative financing options were considered ({{ALTERNATIVES}}) but this loan offers {{ADVANTAGES}}.
5. **Security**: The security/guarantees required are acceptable and do not unduly restrict company operations.
6. **Covenants**: The financial covenants are achievable based on business plan.
7. **Risk**: The debt level after this loan ({{TOTAL_DEBT}}) is manageable considering equity ({{EQUITY}}) and expected performance.

The Board recommends approval."
-->

### Impact on Company Finances

Following this loan, the company's debt structure will be:

| Facility | Lender | Principal | Interest | Maturity | Security |
|----------|--------|-----------|----------|----------|----------|
| {{EXISTING_LOAN_1}} | {{LENDER_1}} | EUR {{PRINCIPAL_1}} | {{RATE_1}}% | {{MATURITY_1}} | {{SECURITY_1}} |
| **New loan** | **{{LENDER}}** | **EUR {{PRINCIPAL}}** | **{{RATE}}%** | **{{MATURITY}}** | **{{SECURITY}}** |
| **Total debt** | | **EUR {{TOTAL_DEBT}}** | | | |

**Key ratios after loan:**
- Debt / Equity: {{DEBT_EQUITY_RATIO}}
- Net Debt / EBITDA: {{ND_EBITDA_RATIO}}x (if applicable)

### Authority to Borrow

{{BORROWING_AUTHORITY}}

<!-- Check Articles:
"The Articles of Association {{ARTICLES_BORROWING}}."

Examples:
- "do not restrict the Board's authority to borrow on behalf of the company"
- "provide that borrowings exceeding EUR {{LIMIT}} require shareholder approval (this loan is within Board's authority)"
- "require shareholder approval for borrowings exceeding EUR {{LIMIT}} (this loan exceeds the limit; shareholder approval was obtained on {{DATE}})"
-->

### Resolution

**The Board resolved to:**

1. **Approve** borrowing EUR {{PRINCIPAL}} from {{LENDER}} on the terms summarized above;
2. **Authorise** {{AUTHORISED_PERSON}} to:
   - Negotiate final terms of the loan agreement consistent with this resolution;
   - Execute the loan agreement, security documents, and all related documents on behalf of the company;
   - Drawdown the loan proceeds; and
   - Take all actions necessary to implement this financing;
3. {{SECURITY_RESOLUTION}};
4. **Determine** that the loan proceeds shall be used for {{PURPOSE}}; and
5. **Note** that the company's total debt after this loan will be EUR {{TOTAL_DEBT}}.

<!-- Security resolution (if applicable):
"**Grant** the security interests specified above in favor of {{LENDER}}"
-->

### Voting

{{VOTING_RECORD}}

### Follow-up Actions

- [ ] {{AUTHORISED_PERSON}} to finalize loan agreement
- [ ] Satisfy conditions precedent
- [ ] Execute loan agreement and security documents
- [ ] Register security interests if required
- [ ] Drawdown loan proceeds
- [ ] Record loan in company's accounts as liability
- [ ] Set up debt service payment calendar
- [ ] Establish compliance monitoring for covenants
- [ ] Provide required reporting to lender
- [ ] {{ADDITIONAL_ACTIONS}}

---

<!--
USAGE NOTES:

Board authority to borrow:
- Generally within Board's authority per OYL 6:2
- Check Articles for any limits or shareholder approval requirements
- Large borrowings may require shareholder approval as strategic decision

Types of loans:
1. **Term loan**: Fixed amount, amortizing or bullet repayment
2. **Revolving facility**: Borrow, repay, re-borrow up to limit
3. **Overdraft**: Bank account overdraft facility
4. **Bridge loan**: Short-term, pending permanent financing
5. **Invoice financing**: Advance against receivables

Security types:
1. **Pledge** (pantti): Over specific assets (shares, inventory, receivables)
2. **Mortgage** (kiinnitys): Over real estate
3. **Floating charge**: Over general business assets
4. **Guarantee** (takaus): Third party promises payment

Financial covenants:
- Ratios or amounts company must maintain
- Tested quarterly, semi-annually, or annually
- Breach = event of default (lender can demand repayment)
- Request waivers if risk of breach

Common covenants:
- Equity ratio (equity / total assets) ≥ X%
- Leverage (debt / EBITDA) ≤ X
- Debt service coverage (EBITDA / debt service) ≥ X
- Minimum liquidity

Negative covenants (restrictions):
- Negative pledge (no new security without consent)
- Dividend restrictions
- Asset sale restrictions
- No additional debt without consent

Best practices:
- Negotiate favorable terms
- Ensure covenants achievable
- Understand consequences of default
- Maintain good lender relationship
- Comply with reporting requirements
- Monitor covenant compliance proactively

REMEMBER to:
- Execute loan agreement and security docs
- Register security interests where required
- Record liability in accounts
- Monitor covenant compliance
- Make timely payments
-->
