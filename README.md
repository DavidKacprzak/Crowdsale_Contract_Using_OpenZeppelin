# Crowdsale_Contract_Using_OpenZeppelin
A crypto token crowdsale using smart contracts and the OpenZeppelin Solidity library. The crowdsale in this example is capped at raising 25 ETH and will run for 5 minutes.

This crowdsale contract manages the entire process allowing users to send ETH and get back PUP (PupperCoin). This contract will mint the tokens automatically and distribute them to buyers in one transaction.



---

## Process for Purchasing PupperCoin

Compile the `Crowdsale.sol` file. This will import the libraries at the top.

![compile](Images/compile.jpg)

Select PupperCoinSaleDeployer in the contract dropdown.

![Select PupperCoinSaleDeployer](Images/SelectPupperCoinSaleDeployer.jpg)

Fill in the name, symbol, funding wallet address, and funding goal. Click transact to deploy the contract. Confirm the transaction when the MetaMask pops open.

![Deployer](Images/DeployPupperCoinSaleDeployer.jpg)

PupperCoinSaleDeployer should apper in the Deployed Contracts sections. Click the `token_sale_address` button and copy the address. Paste the address above in the `At Address` field. Next select `PupperCoinSale` in the contract dropdown. Now click `At Adress`. 

![Select PupperCoinSale](Images/PupperCoinSale.jpg)


A newly deployed contract named PupperCoinSale should appear. Go back to PupperCoinSaleDeployer and click the `token_address` button and copy the address. Paste the address above in the `At Address` field. Next select `PupperCoin` in the contract dropdown. Now click `At Adress`. A new deployed contract named PupperCoin should appear.

![Select PupperCoin](Images/PupperCoin.jpg)

Point MetaMask to a different address.

![Change MetaMaskAccount](Images/SwitchToSecondMetaMaskAccount.jpg)

Add a value and unit of account, for example 25 ether. Insert the benficiary address and click transact to buy PupperCoin tokens! 

![Buy Tokens](Images/buyTokens.jpg)

