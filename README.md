# Solidity
## MyToken
The MyToken contract contains the following variables:

name - name of the token (e.g. "MyToken").
symbol - symbolic designation of the token (e.g. "MTK").
decimals - number of decimal places used to represent token.
totalSupply - the total number of tokens in circulation.
The contract also contains two mappings:

balanceOf - mapping of users' addresses to their token balances.
mapping - mapping users' addresses to users' addresses and the number of tokens they can transfer on behalf of the owner.
The contract defines the following events:

Transfer - the event that is generated for each successful token transfer transaction.
