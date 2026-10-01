1. Project Name:
   UPI ExpensePulse - Expense tracking system
2. Problem Statement:
   Personal UPI Expense Tracker with Automated SMS Parser
3. Project Description:
   College students receive many bank/UPI transaction SMS messages but often do not maintain a proper record of their   spending. SmartSpend converts these transaction messages into structured expenses and provides categorization, budgeting and visualization.
4. Solution:
   By parsing bank SMS notifications automatically, the tracker keeps an accurate record of every micro-transaction without requiring manual entry, preventing students from running out of money without knowing where it went.
5. Key Features:
  -> SMS transaction parsing
  ->Amount extraction
  -> Debit/Credit detection
  -> Merchant/VPA extraction
  -> Date/time extraction
  -> Automatic expense categorization
  -> Food & Dining
  -> Travel
  -> Bills
  -> Shopping
  -> Others
  -> Monthly budget
  -> 80% and 100% budget warnings
  -> Spending charts
  -> Daily spending analysis
  -> Transaction history
  -> CSV/Excel export
  -> Client-side processing
  -> No financial SMS stored on external servers
6. Technology Stack:
   Frontend: HTML
   Styling: Tailwind CSS
   Charts: Recharts
   Storage: LocalStorage
   Deployment: Vercel / GitHub Pages
7. System Architecture:
 User
  ↓
Paste/Upload SMS
  ↓
SMS Parser
  ↓
Regex Extraction
  ↓
Transaction Object
  ↓
Categorization
  ↓
Budget Calculation
  ↓
Dashboard
  ├── Charts
  ├── Budget Warning
  └── Transaction History
8. Privacy & Security:
   100% client-side SMS processing
