# swed-coin
Creating a new ERC20 token using solidity 😮

## Functions Implemented:

balanceOf: Displays the balance of the user's wallet 🤑

transfer: Sends the user's tokens to another wallet 🏧

transferFrom: Allows users to approve a 3rd party to send their tokens to another user 🏛️

allowance: Allow another user to spend tokens on your behalf 👪

## Project Details 👔

This project was inspired by wanting to learn more about how **ERC20** tokens work. 🎓

* I wanted to explore how much freedom developers have with their ERC20 definition

* How to actually create a **new token** 

* How to transfer new tokens to an ether wallet

1. This first step of the project was to implement the 3 standard files needed for a new ERC20 token. 🗂️
    1. Token.sol 
    2. StandardToken.sol
    3. TokenName.sol (swedcoin.sol in my project) 
 
These files were obtained and modified from **open source** sources, and were studied to understand their underlying structure. 🤗

2. The second step was to modify these files to create our new token. 
    1. The files were successfully modified using **Solidity**,
    2. A smart contract was deployed on the Ethereum Virtual Machine (EVM) for a cost of 0.0624 ether, and a genesis block was created.

**Yayyy 😄**

- - - -

![alt text](https://github.com/aliomar/swed-coin/blob/master/pictures/genesis_block.jpg)

- - - -

I decided to create 100,000,000 **swed coins** with a decimal precision of 8 decimal places. 💸

3. The final step was to transfer my new tokens to an ether wallet. I decided to use myetherwallet. 💱
    1. Created a new myetherwallet
    2. Defined **swed coin** as a new custom token
    - - - -
    ![alt text](https://github.com/aliomar/swed-coin/blob/master/pictures/defining_token.JPG)
    - - - -    
    3. Transfered my **swed coin** from the original contract wallet to my newly created ether wallet
    - - - -
   ![alt text](https://github.com/aliomar/swed-coin/blob/master/pictures/transfer.JPG)
    - - - -

### This project was a good intro into Solidity development, and learning the fundamentals of ERC20 tokens. 


💰💰💰
