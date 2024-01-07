## DegenToken Solidity Contract
This Solidity contract implements a basic ERC20 token named DegenToken. It also includes additional functionalities for redeeming items, setting item prices, and listing available items.

## OverView
The contract extends the ERC20 and Ownable contracts from the OpenZeppelin library.
It defines events, mappin## DegenToken Solidity Contract 
## This Solidity contract implements a basic ERC20 token named DegenToken. It also includes additional functionalities for redeeming items, setting item prices, and listing available items.

## OverView
The contract extends the ERC20 and Ownable contracts from the OpenZeppelin library.
It defines events, mappings, and functions to manage tokens and items.

## Functions
mint: Allows the owner to mint new tokens and distribute them to a specified address.
burn: Allows users to burn their own tokens.
redeemItem: Allows users to redeem an item by providing the item name and paying the corresponding price in tokens.
transferCoin: Allows users to transfer tokens to another address.
setItemPrice: Allows the owner to set or update the price of an item.
getItemPrice: Retrieves the price of a specific item.
getUserItem: Retrieves the item owned by a specific user.
listAvailableItems: Lists all available items along with their prices.

## Authors
Aditya Kalaskar 

## License
This project is licensed under the [MIT] License - see the LICENSE.md file for details
