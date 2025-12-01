# Title: Requirements Summary

## Purpose
A backend for a digital bank that handles customer accounts, processes transactions, and supports future growth.

## Scope

### In-scope
- Creating customer accounts
- Getting account details by ID
- Updating accounts info (like email or status)  
- Searching accounts
- Finding if the accounts exist for other services 

### Out-of-scope
- User interface  
- User authentication and login  
- Deposits or withdrawals (TransactionService)
- Making statements (StatementService)
- Sending notifications (NotificationService)

## User/Actors

- TransactionService
- StatementService

## User Stories

- **US-1:** As a new customer, I want to create an account so I can start transacting.  
- **US-2:** As a customer, I want to deposit and withdraw money from my account.  
- **US-3:** As a customer, I want to view a statement of my recent transactions.  
- **US-4:** As a customer, I want to receive an email notification after a significant transaction.  

## Acceptance Criteria (Given / When / Then)

### AC-1
- **Given:** The customer information needed to create an account  
- **When:** The customer requests to create an account  
- **Then:** A new account is created, and the customer can begin depositing money  

### AC-2
- **Given:** The customer’s account and funds  
- **When:** The customer attempts to make a deposit or withdrawal  
- **Then:** The customer is able to complete the transaction  

### AC-3
- **Given:** The customer’s account  
- **When:** The customer attempts to view their transactions  
- **Then:** The customer is shown their recent transactions  

### AC-4
- **Given:** The customer’s account, email, and a large transaction  
- **When:** The customer completes a large transaction  
- **Then:** A notification is sent to the customer about the transaction  
