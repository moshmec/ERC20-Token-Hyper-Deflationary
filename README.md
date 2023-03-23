# ERC20-Token-Hyper-Deflationary
Create Free Token on BSC, ERC20, AVAX, POLYGON
open https://remix.ethereum.org/
create new file, name it whatyouwant.sol
paste contract code
find "contract whatyouwant"
change whatyouwant to your contract name what you want
click solidity complier from left menu
select complier version 0.8.5
compile whatyouwant.sol
click "Deploy and Run transactions" from left menu
click ENVIRONMENT and select Injected Provider - Metamask 
select whatyouwant - whatyouwant.sol (not ownable or address or etc) from contacts menu
expand deploy section
write your tokens name,total supply, etc
_N : Name , _S Symbol , _D Decimal, _TS Total Supply, _TAX TAX, _BB Buyback TAX, _MKT Marketing Fee (Marketing fee can not be less than 0.5%), _MA marketin address
TAX Example, 20 means %2 ; Total Supply example, If you write 18 for decimal , add 18 "0" to end. For 1000 supply; 1000000000000000000000...
click transact
