# Non-Collaterized Loans DeFi



![non_col_loans1](Images/non_col_loans1.png)



Defi usually has seen only Collaterized Loans. this means either you already have some Crypto like Bitcoin or Ethereum or various others and usually you can borrow against it. and you can borrow depending on the protocol or Dapp around 50% of it.

But this means that they already have that amount of currency to borrow against.

DeFi currentlly does not give non-collaterized loans.

But most loans in real world like Auto loans, Mortgage etc are non-collaterized loans meaning the borrower is not depositing any money to take this loan. The asset to some degree can serve as collateral on non-payment but these loans and terms are given based on their.

This project will solve that issue.



### Chainlink Any APi

We will be writing a Chainlink Any APi to interface with Equifax credit reporting agency. We will use their Sandbox to get some ficticious credit scores.

https://api.consumer.equifax.com/saas/docs/api/index.html



![image-20211117155629649](/Users/chakravartiraghavan/Documents/pepperdinegitlab/Github/NonCollaterizedLoansDeFi/Images/ChainLinkAnyApi.png)



### Solidity / Remix - Non Collaterized Loan Smart Contract

This credit score will be brought in to a Non-Collaterized Loan Smart contract and will be minted as a Non-Fungible token.

Each borrower will be an NFT with additional attributes of loan amounts from the lender and minimum amounts, and other terms etc.

Lenders can view different borrowers with each credit score. and can decide which one they want to lend to.

An Algorithm with calculate the borrowing rate for the borrower as interest and also same for the lender what kind of interest and monthly payments they can get.

Things will be kept simple for this project that can later be expanded.



### Web3 Python / Steamlit UI

Web3 Python will be used to provide interface for the Borrower to first establish their credit score and then to place the contract. Then also for lenders to check which borrowers are still looking for taking loans and can choose to lend.



If the borrower does not pay then this will be reported back to Equifax and off-chain collections will be done etc. this will not be in  scope for this project at the moment.





### 



 



