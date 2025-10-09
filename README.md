## Instruction
You are Matthew Moore, a finance officer, with the email matthew.moore@investment.com. You want to create a new NAV record for the fund 'Green-Wright Growth Fund' with a NAV value of $165.50 for the date September 30, 2025. Once the NAV record is created, you want to retrieve all NAV records for this fund from September 2025 to verify the new record was added correctly.

**Total Edges = 16**

---

## Some of the policies which had while creating a task:

### 1. NAV Record Creation 
* **Policy:** Verify that approval is present using check_approval (Finance Officer approval required for creation)
* **Application:** Finance officer approval validated before creating NAV record for September 30, 2025

### 2. Direct Authorization for Finance Officers
* **Policy:** Users with approval authority for a specific action can execute that action without requiring additional approval from their own role
* **Application:** Matthew Moore (finance_officer) directly authorized for nav_record_creation action

### 3. Fund Existence Verification
* **Policy:** Verify that the fund exists using search_fund_entities
* **Application:** Green-Wright Growth Fund verified to exist before NAV record creation

### 4. NAV Record Retrieval for Verification
* **Policy:** Calculate NAV using handle_nav_record when instructed to do so; otherwise retrieve using search_valuation_entities
* **Application:** All NAV records for fund retrieved after creation to verify new record was added correctly

### 5. Audit Trail Compliance
* **Policy:** Create an audit entry for the NAV event using add_new_audit_trail
* **Application:** Audit trail entry (3502) created to log NAV record creation event

### 6. Entity Discovery Before Operations
* **Policy:** Verify entity existence before operations using appropriate search tools
* **Application:** User (Matthew Moore) and fund (Green-Wright Growth Fund) entities verified before NAV creation

---

## Task Details
- **Environment:** fund_finance
- **Interface:** 2
- **User ID:** 8
- **Complexity:** Expert (16 edges)
- **Total Actions:** 6
- **Total Edges:** 16
<img width="5454" height="3125" alt="image" src="https://github.com/user-attachments/assets/63941724-1503-422f-a162-48ec261095bb" />
