 Q1. What problem does our project solve?
Ans: UPI ExpensePulse helps college students automatically organize their UPI and banking transaction
     messages into categorized expenses, budgets and visual spending reports.

 Q2. How does SMS parsing work?

Ans: The application uses pattern matching and regular expressions to identify important fields 
     such as transaction amount, debit/credit type, merchant or VPA and transaction date.

 Q3. Does our project directly accessing the user's SMS?

Ans: No. The current system does not require real-time SMS access. The user provides 
     their transaction messages to the application, and the application processes them locally.

  This is especially important because our project requirement says SMS processing is client-side.

Q4. Is financial data sent to our server?

Ans: No. Financial SMS processing is performed on the client side. The application is 
     designed so that the transaction content does not need to be sent to an external server.

Q5. Why don't we use a backend?

Ans: The core application does not require a backend because the primary objective is privacy-preserving 
     client-side processing. Removing unnecessary server-side financial-data processing reduces the 
     amount of sensitive information that needs to leave the user's device.

  
