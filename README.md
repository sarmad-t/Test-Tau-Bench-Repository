## Instruction
You are Patricia Miller, a trader, with the email patriciamiller@gmail.com. You want to update the price information for the instrument 'Torres Glover and Green Ltd' with ticker CIR7 for the date October 1, 2025. The price details should be open price $46.50, high price $49.20, low price $45.80, and close price $48.75.

**Total Edges = 11**

---

## Some of the policies which had while creating a task:

### 1. Instrument Price Updates
* **Policy:** Verify that approval is present using check_approval (Fund Manager and Compliance Officer approvals required)
* **Application:** Dual approval (Fund Manager and Compliance Officer) validated before creating instrument price record

### 2. Instrument Existence Verification
* **Policy:** Verify that the instrument exists using search_instrument_entities
* **Application:** Instrument 'Torres Glover and Green Ltd' (ticker CIR7) verified to exist before price update

### 3. Duplicate Price Record Prevention
* **Policy:** Check for existing price records for the date using search_valuation_entities
* **Application:** System verified no existing price record for October 1, 2025 before creating new price entry

### 4. Audit Trail Compliance
* **Policy:** Create an audit entry for price update using add_new_audit_trail
* **Application:** Audit trail entry (3501) created for instrument price creation event

### 5. Entity Discovery Before Operations
* **Policy:** Verify entity existence before operations using appropriate search tools
* **Application:** User (Patricia Miller) and instrument entities verified before processing price update
---

## Task Details
- **Environment:** fund_finance
- **Interface:** 2
- **User ID:** 3
- **Complexity:** Medium (11 edges)
- **Total Actions:** 6
- **Total Edges:** 11


<img width="9385" height="2375" alt="image" src="https://github.com/user-attachments/assets/cddc311f-8f74-42ff-b867-b41a60b7ca11" />

