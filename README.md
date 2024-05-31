<h2>Python: financial audit project<h2></h2>

FINTRAC (Financial Transactions and Reports Analysis Centre of Canada) is Canada’s financial intelligence unit, that assists in the detection, prevention and deterrence of money laundering and the financing of terrorist activities. As part of one of the FINTRAC regulatory requirements, financial institutions must report all EFT transactions (Electronic Funds Transfers) made at the request of a client through the SWIFT network. 

EFT-SWIFT transactions must be reported to FINTRAC if one of the following conditions is met: 
Single EFT transactions with SWIFT transaction type exceeding $10,000;
Two or more EFT-SWIFT transactions that were made within 24 hours (less than $10,000 each) exceeding $10,000 in total. 

You’ve received two files from the Bank department: 
1) Data for all EFT transactions for the full audit period (“eft.csv”) 
2) Transactions that Bank reported to FINTRAC during the audit period (“fintrac_reported.xlsx”) 

The task is to: 
Explore the transactions data and share any noted observations;
Verify that the Bank has reported all EFT-SWIFT transactions timely (reporting date is expected to be the same as transaction date) and accurately (reported transaction date and amount must be matching eft data). 

Cases, when transactions weren’t reported timely or accurately, will be considered audit observations and should be presented to the Bank staff with the goal of further investigation. 
