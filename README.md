
# Smart Contract Managment
This repository includes a Solidity smart contract named BankATM that offers fundamental banking services like deposits, withdrawals, and account balance retrieval. A frontend solution for interacting with the contract on the Ethereum blockchain is also included in the contract.





## Contract Functionality


Smart Contract for BankATM
This repository includes a Solidity smart contract named BankATM that offers fundamental banking services like deposits, withdrawals, and account balance retrieval. A frontend solution for interacting with the contract on the Ethereum blockchain is also included in the contract.

Details about Smart Contract 
The BankATM contract has the following functions:

1. deposit(uint256 _amount): Allows the owner to deposit Ether into the account.
2. withdraw(uint256 _withdrawAmount): Allows the owner to withdraw Ether from the account.
3. getBalance(): Returns the current account balance.
4. getOwner(): Returns the address of the account owner.
## DEPLOYMENT
Create a hardhat project, add a contract to it, run your blockchain through Goerli Testnet, and then write the code for the front end and connect the back end with the front end using the artefacts abi.
Run the fronted now and verify all capability. 
Also, if your contract address changes during a DEPLOYMENT, update it in the contract address field in front.
## Install
hardhat installation

1. npm install --save-dev hardhat

2. npx hardhat 

3. Create a javascript project 

4. write the contract 

5. Run the blockchain

6. Deploy the contract 
   npx hardhat run scripts/deploy.js --network goerli 

7. Make a frontend page and implement all the function in the code 

8. Now entere your contract address
   
9. enter you abi 
10. run your project
11. Test the project by connecting your wallet
12. Make sure you have the testnet amount present in wallet whatever the network you are deploying




## Author
Nikhil Upadhyay
