# English Test Cases for AI Contract Clause Builder

## Quick Test Cases (3 scenarios)

### Test Case 1: Liability Limitation (Basic Test - No Documents)

**Clause Drafting Objective:**
```
Limit liability for indirect, special, or consequential damages to a maximum of 20% of the total contract amount, and specify exclusions from liability.
```

**Jurisdiction:**
```
United States
```

**Upload Reference Documents:**
```
(No upload)
```

**Drafting Style:**
```
Balanced (Legal but Readable)
```

**Number of Automated Reviews:**
```
2
```

**Expected Results:**
- AI Calls: 7 times
- Generated clause should include:
  - Definition of indirect/consequential damages
  - 20% liability cap
  - Exclusion list
  - Calculation basis

---

### Test Case 2: Liquidated Damages (With Documents)

**Clause Drafting Objective:**
```
Establish liquidated damages provision with daily calculation method, not to exceed 24% annual rate, and specify payment deadlines.
```

**Jurisdiction:**
```
England and Wales
```

**Upload Reference Documents:**

**Document: liquidated_damages_reference.txt**
```
LIQUIDATED DAMAGES LEGAL REFERENCE

1. LEGAL BASIS
Liquidated damages are pre-determined compensation amounts specified in contracts for breach. 
They must represent a genuine pre-estimate of loss and not constitute a penalty.

2. KEY PRINCIPLES
- Must be proportionate to anticipated harm
- Cannot be punitive in nature
- Should be stated clearly and unambiguously
- Courts may reduce if deemed excessive

3. CALCULATION METHODS
Common approaches include:
a) Fixed amount per breach
b) Daily rate until remedy
c) Percentage of contract value
d) Graduated scale based on delay period

4. ENFORCEABILITY FACTORS
Courts consider:
- Commercial justification
- Reasonableness of amount
- Relationship to actual losses
- Good faith negotiations

5. SAMPLE CLAUSE
"In the event of Contractor's failure to complete the Works by the Completion Date,
Contractor shall pay to Employer liquidated damages at the rate of [£X] per day
of delay, up to a maximum of [Y%] of the Contract Price."

6. BEST PRACTICES
- Clearly state triggering events
- Specify calculation methodology
- Include maximum caps
- Distinguish from penalties
- Address mitigation duties
```

**Drafting Style:**
```
Legal Formal
```

**Number of Automated Reviews:**
```
2
```

**Expected Results:**
- AI Calls: 9 times (includes document summary + retrieval)
- Clause should reference uploaded document
- Formal legal language style
- Include calculation formula and caps

---

### Test Case 3: Confidentiality Obligations (Complex Test)

**Clause Drafting Objective:**
```
Define confidential information scope, confidentiality obligations, duration (3 years post-termination), exceptions, and breach remedies including injunctive relief.
```

**Jurisdiction:**
```
Singapore
```

**Upload Reference Documents:**

**Document 1: confidentiality_guide.txt**
```
CONFIDENTIALITY CLAUSE DRAFTING GUIDE

I. DEFINITION OF CONFIDENTIAL INFORMATION

Confidential Information typically includes:

1. Business Information
   - Business plans and strategies
   - Customer and supplier lists
   - Pricing and financial data
   - Marketing plans and analysis

2. Technical Information
   - Technical specifications and designs
   - Source code and algorithms
   - Product specifications
   - Research and development data

3. Financial Information
   - Financial statements
   - Investment plans
   - Budgets and forecasts

II. OBLIGATIONS

The Receiving Party must:
1. Not disclose to third parties
2. Use only for authorized purposes
3. Implement reasonable security measures
4. Require employees to sign NDAs
5. Notify discloser of any breaches

III. STANDARD EXCEPTIONS

Information is not confidential if:
1. Publicly available at time of disclosure
2. Becomes public through no fault of recipient
3. Lawfully obtained from third party
4. Independently developed
5. Required by law to be disclosed (with prior notice)

IV. DURATION

Common confidentiality periods:
- General business information: 2-3 years
- Trade secrets: 5-10 years or indefinite
- Technical information: 3-5 years

V. REMEDIES

Breach may result in:
1. Monetary damages
2. Injunctive relief
3. Return of materials
4. Indemnification

VI. SAMPLE CLAUSE

"The Receiving Party agrees to hold in confidence and not disclose
to any third party any Confidential Information disclosed by the
Disclosing Party. This obligation shall survive termination of this
Agreement and continue for a period of [X] years thereafter."
```

**Document 2: singapore_law_notes.txt**
```
SINGAPORE LAW - CONFIDENTIALITY OBLIGATIONS

1. LEGAL FRAMEWORK
Singapore law recognizes confidentiality obligations through:
- Contract law
- Equity (breach of confidence)
- Common law principles

2. ENFORCEABILITY REQUIREMENTS
For enforceability, clauses must:
- Clearly define confidential information
- Specify reasonable duration
- Not be contrary to public policy
- Be reasonable in scope

3. INJUNCTIVE RELIEF
Singapore Courts readily grant injunctions for:
- Threatened disclosure
- Ongoing breaches
- Irreparable harm situations

Requirements:
- Existence of confidential relationship
- Unauthorized use or disclosure
- Detriment to confiding party

4. REMEDIES AVAILABLE
- Injunction (interim and permanent)
- Damages or account of profits
- Return/destruction of materials
- Anton Piller orders (search and seizure)

5. NOTABLE CASES
Courts have enforced confidentiality for:
- Customer databases
- Technical know-how
- Business strategies
- Financial information

6. POST-EMPLOYMENT RESTRICTIONS
Confidentiality duties continue after employment ends.
Courts balance:
- Legitimate business interests
- Employee's right to work
- Reasonableness of restrictions
```

**Drafting Style:**
```
Balanced (Legal but Readable)
```

**Number of Automated Reviews:**
```
3
```

**Expected Results:**
- AI Calls: 10 times
- Comprehensive confidentiality clause
- 3-year post-termination period
- Exception list included
- Singapore law compliant
- Injunctive relief provision

---

## Testing Checklist

### Before Testing
- [ ] API key ready and has sufficient balance
- [ ] Application is running (http://localhost:8501)
- [ ] Documents prepared (copy from above and save as .txt files)

### For Each Test Case
1. [ ] Enter API key in sidebar
2. [ ] Copy-paste the objective
3. [ ] Enter jurisdiction
4. [ ] Upload document(s) if required
5. [ ] Select drafting style
6. [ ] Set number of reviews
7. [ ] Click "Generate Clause"
8. [ ] Wait 1-3 minutes
9. [ ] Verify AI call count
10. [ ] Review generated clause
11. [ ] Download Word document
12. [ ] Check quality assessment

### Success Criteria
- [ ] No errors during execution
- [ ] AI call count matches expectation
- [ ] Clause is relevant to objective
- [ ] Language matches selected style
- [ ] Word document opens correctly
- [ ] Quality assessment shows 10 dimensions

---

## Expected Output Format

### Step 1: Objective Analysis
Should list 5 key drafting points

### Step 2: Document Analysis
- If documents uploaded: summary + retrieval results
- If no documents: legal background research

### Step 3: Constraints Analysis
- Section A: Mandatory elements
- Section B: Optional enhancements
- Section C: Risks to avoid
- Section D: Wording recommendations

### Step 4: Initial Draft
Should include:
- Main clause text
- Drafting notes (3 bullets)

### Step 5: Reviews (2-3 iterations)
Each review shows:
- Revised clause
- Revision notes

### Step 6: Final Version
- Complete final clause
- Word download button

### Step 7: Quality Assessment
- 10 dimension scores (X/10 each)
- Total score (XX/100)
- Strengths (3 points)
- Improvement suggestions (3 points)

---

## Word Document Verification

Check that the Word document contains:
- [ ] Title: "CONTRACT CLAUSE" (centered, Times New Roman, 16pt)
- [ ] Section: "DOCUMENT INFORMATION"
  - [ ] Date Generated
  - [ ] Drafting Objective
  - [ ] Jurisdiction
  - [ ] Drafting Style
- [ ] Section: "CLAUSE PROVISIONS"
  - [ ] Full clause text
  - [ ] Times New Roman, 11pt
  - [ ] 1.5 line spacing
- [ ] Section: "DISCLAIMER"
  - [ ] Professional disclaimer text
  - [ ] Times New Roman, 9pt, italic

---

## Screenshot Checklist

For demonstration, capture:
1. [ ] Main page (title and description)
2. [ ] Sidebar with inputs filled
3. [ ] Step 1 output (Objective Analysis)
4. [ ] Step 4 output (Initial Draft)
5. [ ] Step 7 output (Quality Assessment)
6. [ ] Final statistics display
7. [ ] Downloaded Word document (first page)

---

## Quick Reference

| Test | AI Calls | Documents | Style | Jurisdiction |
|------|----------|-----------|-------|--------------|
| 1 | 7 | None | Balanced | US |
| 2 | 9 | 1 file | Formal | UK |
| 3 | 10 | 2 files | Balanced | Singapore |

---

**Ready to test! Start with Test Case 1 (simplest) to verify basic functionality.** ✅

