# Metacrafters
This is explaination of projects for each module

#Projects
**JavaScript**
**Solidity** contains _Etherium Beginner
_

# Readme File for Solidity_MyToken
In this file, We have Created Token with transactions. Transactions includes Addituon of amount in Balance or Deduction of amount from it by sender.
**Requirements**

1) Public String Variables named as TokenName and TokenAbbrv
2) Unsigned Integer named as TotalSupply which has initial value 0
3) For mapping of address to balances; we used mapping keyword.
4) For Transactions, we require 2 functions:
   For adding amount : mint function
   For deducting amount: burn function
5) Mint function uses increment operator where total supply increases by value and balance will increase by amount.
6) **Take Precaution in burn function** because amount will never be negative so we added condition here which states that
if balance is greater than or equal to burn value then and then only this burn function will execute.
The functioning of burn function:
Opposite of mint function in which decrement operator is used by decraesing total supply by value and decreasing balance by amount

On the basis of this we programmed on IDE.

#Working
Click on complile button on IDE and deploy it.
Copy the address of sender and paste in address section of mint and burn function
Put the value in mint and burn and do transactions

**Observe blue tick on output section while performing any operation**
**If this blue tick appears that means your code is working properly**

# For Better Understanding Loom Link is here
I have mentioned Explaination of code with workin on loom link
https://www.loom.com/share/9173cd2705aa48e6bcada494e07027aa




