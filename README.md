# Project Name: DMoney API Testing

## Project Description:
This is a basic API testing project. Here in this projec -
- Created 2 customers and 1 agent using API
- Activated all users using Admin API
- Deposited 5000 TK from the system account to the agent account
- Agent deposited 2000 TK to a customer account
- One customer sent 1000 TK to another customer
- Another customer performed a cash out of 500 TK from the agent account
- For positive test cases User activation,Deposit transaction, Send money transaction, Cash out transaction were implemented.
- For negative test cases Unauthorized transactions,Insufficient balance,Invalid accountInvalid token/authentication,Failed transaction validation
were implemented.

 ### Technology used:
 - NodeJS
 - Postman
 - Newman
 - HTML Report Extra

### How to Run:
- `npm init -y`
- `node report.js`
- `npx newman run DMoney_apiAssignment.postman_collection.json`
- `npx newman run DMoney_apiAssignment.postman_collection.json -r htmlextra`

### API Documentation
[click for API Documentation](https://documenter.getpostman.com/view/54498088/2sBXqQEHJf)

### Report
<img width="950" height="890" alt="api_report2_assignment" src="https://github.com/user-attachments/assets/81b48c2a-9a52-44f2-861c-f0448c7105fc" />
