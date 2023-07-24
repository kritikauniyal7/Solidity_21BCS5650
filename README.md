# Create a Token

This Solidity programme is a helpful "Create Token" programme that shows users how to begin using the language and create a token. It also teaches the fundamental syntax and features of the Solidity programming language. This program's goal is to provide background knowledge about solidity.

## Description

This is a basic program  which is written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain.The contract contains two "mint and burn" functions; one raises the supply overall and the balance, while the other eliminates the token. This programme offers a suitable introduction to and opportunity for Solidity programming practise.

## Getting Started

### Executing Program

I used Remix, an online Solidity IDE, to run this programme. Visit the Remix website at https://remix.ethereum.org to get started.
I have added a new file by selecting the "+" icon on the left-hand sidebar once the Remix website has been opened. Save the document as myToken.sol and give it the extension.  Next, I copied and pasted the given code into the file and wrote the required coding lines to successfully complete the project.

Now, the Public variables in my contract will be used to store the information about my coin 
(Token Name, Token Abbrv., and Total Supply).
Token Name-"Happy"
Token Abbrv.-"hpy"
Totalsupply(Initially)-0
The variables Token Name and Token Abbrv. are of string type and totalsupply is an integer type variable.

Addresses will be mapped to balances in my contract using the formula address => uint.

A mint function I created has two inputs: an address and a value. 
The function then increases the balance of the address by that amount 
and increases the total supply by that amount.

Burn Function-As opposed to the mint function, which creates tokens, my contract will contain a burn function.
An address and a value will be required, just like how Mint works. 
The value will then be subtracted from both the address's remaining balance and the total supply.
                             In addition, my burn function needs conditionals to guarantee that
the account balance is morethan or equal to the amount that should be burned.
 The condition used for it : if (balances[_address]>= _value)

 ## License
 My project is licensed under the MIT License-see the LICENSE.md file for details

