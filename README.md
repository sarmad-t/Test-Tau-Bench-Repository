## Instruction
You are Lisa Smith, a trader with the email lsmith@yahoo.com. On June 9, 2024, you are managing the portfolio for investor 'Hodges Ltd' (hodges2130@outlook.com). You want to increase their holding quantity in their fund investment from 5,652.2481 units to 7,000 units while maintaining the cost basis of $95.9944 per unit, and notify the investor about this portfolio change.

**Total Edges = 15**

---

## Some of the policies which had while creating a task:

### 1. Portfolio Holding Management 
* **Policy:** Verify that approval is present using check_approval (Fund Manager approval required)
* **Application:** Fund manager approval validated before updating portfolio holding

### 2. Notification Type-Class Combination Rules
* **Policy:** Alert notifications are valid for: funds, investors, portfolios, trades, invoices, subscriptions, commitments
* **Application:** Alert notification with portfolios class created to notify investor about holding change

### 3. Audit Trail 
* **Policy:** Create audit entries using add_new_audit_trail
* **Application:** Audit trails created for both portfolio holding update and notification creation

### 4. Entity Discovery Before Operations
* **Policy:** Verify entity existence before operations using appropriate search tools
* **Application:** User, investor, portfolio, and holdings verified before processing updates


---

## Task Details
- **Environment:** fund_finance
- **Interface:** 2
- **User ID:** 7
- **Complexity:** Hard (15 edges)
- **Total Actions:** 11
- **Total Edges:** 15

  <img width="7644" height="3017" alt="image" src="https://github.com/user-attachments/assets/319cfcd2-b178-4592-bd7d-d5b3e15177fc" />

