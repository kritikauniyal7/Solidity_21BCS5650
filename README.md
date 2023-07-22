Getting Started with Solidity- In this project project I was asked to create a token using remix-Ethereum IDE,
Public variables in my contract will be used to store the information about my coin 
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

