Title: AccountService - 
Purpose: A backend for a digital bank that handles customer accounts, processes transactions, and helps with future growth
Scope: 
  In-scope:
    Creating and managing accounts
    Processing deposits and withdrawals
    Generating account statements
    Sending notifications about account activity
    
  Out-of-scope:
    User interface
    User authentication and login
    Dealing with loans, credit cards, and investments
  
User/Actors:
  Primary user(s)/system(s): Transaction Service contact
  
User Stories (3-5)
  US-1: As a new customer, I want to be able to create an account so I can start transacting.
  US-2: As a customer, I want to be able to deposit and withdraw money from my account.
  US-3: As a customer, I want to be able to view a statement of my recent transactions.
  US-4: As a customer, I want to receive an email notification after a significant transaction.

Acceptance Criteria (Given/When/Then):
  AC-1
    Given: The customer information needed to make an account
    When: The customer is requesting to make an account
    Then: A new account for the customer is created, and they are able to start depositing money into their account

  AC-2
    Given: The account and the money of the customer
    When: The customer is trying to make a transaction or deposit into their account
    Then: The customer is able to do that action

  AC-3:
    Given: The customer's account
    When: The customer tries to see their transactions
    Then: The customer is brought to the correct recent transactions

  AC-4:
    Given: The customer account, email, and a big transaction
    When: The customer makes a big transaction
    Then: A notice is sent to that customer about the big transactions that were made
  
