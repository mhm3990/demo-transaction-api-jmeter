# demo-transaction-api-jmeter-by-Mahmudul-Mahadi

## Project Summary:
In this project I have done testing on demo transaction api using jmeter

## Scenario
Based on following scenario, created a JMX file and created positive test cases based on this flow.
- Admin creates an agent and a customer
- Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
- Deposit 1000 tk to customer from agent account
- Check balance from customer account
- Withdraw 500 tk from customer account
- Payment 200 tk from customer account (Merchant account: 01686606905)
- Assert expected customer balance

## Technology used:
- jmeter
- jdk 11 

## How to run:
- ``` git clone ```
- ``` save jmax file in bin folder of jmeter ```
- ``` run the jmax file using jmeter ```

## HTML Report
-Command for generating HTML report:
jmeter -n -t demo-transaction-api.jmx -l demo-transaction-api-log.csv -e -o Reports

![demo-transaction-api](https://github.com/mhm3990/demo-transaction-api-jmeter/assets/48542736/aa6c16b3-4c2a-4b2e-8cf4-8501b635a228)
