# secured-overnight-reference-rate-blockchain
Exploring Repo Interbank Reference Rates on the blockchain

Blockchain alternative to LIBOR : SORRB (secured overnight reference rate blockchain). 

This will represent the overnight cost of financing collateralized by Treasury securities. 
1. It will be based on real transactions so that institutions can’t just jack up rates. 
2. It will be volume weighted so bias to create outliers using small volume transactions is removed. 
3. It will remove certain specials like REPOs, that are collateralized with specific securities etc. which tend to have a lower interest rate by design. 
4. It will remove the trades between affiliated entities and trades not done at arm’s length to remove the bias. 
5. It will remove the transactions where FED is one of the counter party to represent the inter bank lending only. 
6. The underlying transaction data will need to be aggregated from trade repositories.
7. It will cover the aggregate volume of tri-party and cleared bilateral activity.
