# Project Title: Automate a demo fintech transaction API by JMETER
## Project Name: Dmoney

Project Summary: This system integrates various financial services, enabling users to manage their finances efficiently and securely from a single application. There are four types of users like Admin, Agent, Customer, and Merchant. 
In this project, I have created a flow where the admin can log in and create new users, and perform several CRUD actions for the users. Also, the users can perform several transactions like send money, deposit, withdraw, payment etc. and check their own balance and statements. 
The Agent can deposit money to the Customer account and another Agent account, and pay Merchant bill.
The customer can send money to the other customer, withdraw money from an agent and they can pay their Merchant bill. 
Merchant receives their bill and they can withdraw their money from the Agent.

## Prerequisites:

- jdk (Latest LTS)
- Jmeter

## How to run?

### Execute following commands:

- `git clone <repo_url>`
- `./jmeter` (For Linux) or
- `.jmeter` (For windows)
  
## How to generate report
  
### For JMeter 5.1.1 version or higher:
To generate the report in Non-GUI mode, execute the test using the below command:
- For Windows:jmeter -n -t 'your JMX file path' -l 'log file path' -e -o 'Path to output folder'
- For Linux: ./jmeter.sh -n -t “<test JMX file path>” -l “<test log file path>” -e -o “<Path to output folder>”
  
The output folder contains the generated report in HTML format at the end of the test.

## Documentation

### Acceptance criteria:

## Output:
![Dmoney perfomance Report](https://github.com/Monira07/demo-transaction-api-jmeter/assets/115618518/3e86d77c-6dc9-4182-a282-7128b50010d2)


