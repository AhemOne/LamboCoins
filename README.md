# LamboCoins
## The Ferrari of Altcoins - An ultra-limited supply collector's edition altcoin for the astute crypto-wizard

:fuelpump::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car:
:blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::fuelpump:

### Closing Date
```
When all Lamborghinis are sold!
```

### Whats this project all about?
:thumbsup: Ultra limited edition, only 250 Lamborghinis released publicly!

:thumbsup: the ORIGINAL collector coin!

:thumbsup: 6 coins are retained for the developers (< 2.5% of all Lamborghinis, we're not greedy).

:thumbsup: 256 total Lamborghinis.

:thumbsup: Lamborghinis are distributed first come, first serve.

:thumbsup: Lamborghinis are tradable as soon as you buy them!

:thumbsup: each successive lamborghini is cost `price * interest rate` more. Don't miss out!!

:thumbsup: Ensure you withdraw all your remaining funds. The ICO will end as last Lamborghini is sold, but a grace period will be allowed for users to withdraw their remaining funds before the ICO contract is shut down.

:thumbsup: LamboCoin is an unowned ERC20 compliant contract, it will never selfdestruct and you can trade it as you wish!

:thumbsup: Adopters get special rewards in our future games!

### What's the details?
#### LamboCoin
  **Contract Address:** `0xefd988452f4a780919734e8f9cee589afe09e78b` [Etherscan](https://etherscan.io/address/0xefd988452f4a780919734e8f9cee589afe09e78b) 
  
  _Note: LamboCoin manages the ICO in a separate contract_
  
  Add this address to your wallet interface to transfer your Lamborghinis. This is a ERC20 compliant token so may be traded at will. Lamborghinis are assigned upon purchase and are available to trade straight away!. This address will _not_ accept Ether. Please buy Lamborghinis from the ICO address above.

  :vertical_traffic_light: JSON Interface; copy the code below to your preferred wallet interface to access the trade functionality
  ```
  [ { "constant": true, "inputs": [], "name": "name", "outputs": [ { "name": "", "type": "string" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": false, "inputs": [ { "name": "spender", "type": "address" }, { "name": "value", "type": "uint256" } ], "name": "approve", "outputs": [ { "name": "success", "type": "bool" } ], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": true, "inputs": [], "name": "totalSupply", "outputs": [ { "name": "", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": false, "inputs": [ { "name": "from", "type": "address" }, { "name": "to", "type": "address" }, { "name": "value", "type": "uint256" } ], "name": "transferFrom", "outputs": [ { "name": "success", "type": "bool" } ], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": true, "inputs": [], "name": "ICO", "outputs": [ { "name": "", "type": "address" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "decimals", "outputs": [ { "name": "", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [ { "name": "who", "type": "address" } ], "name": "balanceOf", "outputs": [ { "name": "", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "symbol", "outputs": [ { "name": "", "type": "string" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": false, "inputs": [ { "name": "to", "type": "address" }, { "name": "value", "type": "uint256" } ], "name": "transfer", "outputs": [ { "name": "success", "type": "bool" } ], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": true, "inputs": [ { "name": "owner", "type": "address" }, { "name": "spender", "type": "address" } ], "name": "allowance", "outputs": [ { "name": "", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "anonymous": false, "inputs": [], "name": "ICOIsOver", "type": "event" }, { "anonymous": false, "inputs": [ { "indexed": true, "name": "from", "type": "address" }, { "indexed": true, "name": "to", "type": "address" }, { "indexed": false, "name": "value", "type": "uint256" } ], "name": "Transfer", "type": "event" }, { "anonymous": false, "inputs": [ { "indexed": true, "name": "owner", "type": "address" }, { "indexed": true, "name": "spender", "type": "address" }, { "indexed": false, "name": "value", "type": "uint256" } ], "name": "Approval", "type": "event" } ]
  ```

#### Initial Coin Offering (ICO):

  **Contract Address:** `0xfe97fd8e9375f1463544c22fb78d895ad1c668a9` [Etherscan](https://etherscan.io/address/0xfe97fd8e9375f1463544c22fb78d895ad1c668a9)

  Send Ether to this address to get your Lamborghinis! Use the pay() function in your wallet interface to buy multiple coins at a time, ether sent directly will only allow the purchase of a _single_ Lamborghini at a time. The ICO contact constitutes a basic token so you can add it to your watched tokens list and doing show will display how much ether left over Ether is available to you for withdrawal. _Please withdraw your remaining funds before the ICO end date posted above or risk losing it!_
  
  :vertical_traffic_light: JSON Interface; copy the code below to your preferred wallet interface to access the functionality
  ```
  [ { "constant": true, "inputs": [], "name": "name", "outputs": [ { "name": "", "type": "string" } ], "payable": false, "stateMutability": "pure", "type": "function" }, { "constant": true, "inputs": [], "name": "coin", "outputs": [ { "name": "", "type": "address" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": false, "inputs": [ { "name": "amount", "type": "uint256" } ], "name": "withdraw", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": true, "inputs": [], "name": "decimals", "outputs": [ { "name": "", "type": "uint256" } ], "payable": false, "stateMutability": "pure", "type": "function" }, { "constant": true, "inputs": [], "name": "priceGuice", "outputs": [  { "name": "unsoldCoins", "type": "uint256" }, { "name": "currentPrice", "type": "uint256" }, { "name": "nextPrice", "type": "uint256" }, { "name": "InterestRateNumerator", "type": "uint256" }, { "name": "InterestRateDenominator", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [ { "name": "who", "type": "address" } ], "name": "balanceOf", "outputs": [ { "name": "", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "symbol", "outputs": [ { "name": "", "type": "string" } ], "payable": false, "stateMutability": "pure", "type": "function" }, { "constant": false, "inputs": [], "name": "buy", "outputs": [], "payable": true, "stateMutability": "payable", "type": "function" }, { "payable": true, "stateMutability": "payable", "type": "fallback" }, { "anonymous": false, "inputs": [ { "indexed": false, "name": "person", "type": "address" }, { "indexed": false, "name": "amount", "type": "uint256" } ], "name": "WithdrawalOfFunds", "type": "event" }, { "anonymous": false, "inputs": [ { "indexed": false, "name": "number", "type": "uint256" } ], "name": "CoinsSold", "type": "event" }, { "anonymous": false, "inputs": [], "name": "ICOIsOver", "type": "event" }, { "anonymous": false, "inputs": [ { "indexed": false, "name": "newNum", "type": "uint256" }, { "indexed": false, "name": "newDenom", "type": "uint256" } ], "name": "InterestRateChange", "type": "event" } ]
  ```

### FAQ
:vertical_traffic_light: **Why Lamborghini?**

The first car any cryptomillionaire must buy is obviously a Lamborghini, so logically the original ultra rare coin should be based on them. This coin will also provide investors with bonuses when our games are released to thank you for helping our cause.

:vertical_traffic_light: **Why only 256 coins?**

For Exclusivity, Like a real Lamborghini each coin is exclusive and made in limited numbers. This IGO is the only IGO that will occur meaning you will be one of the elite few who can have the privelege of owning one (or many, depending on how much Ether you have). 256 was chosen because it is equal to 2^8, it's an awesome number.

:vertical_traffic_light: **How do I get them?**

Add the ICO contract above to your ethereum client to purchase. Single coins may be purchased by sending the current price in ether directly to the contract, multiple coin purchases require the ICO interface or use our ~~Website~~ (coming soon!).

:vertical_traffic_light: **Will I get my left over Ether back?**

You may withdraw funds up until the ICO contract is finished. After this time any remaining funds can no longer be refunded as the contract will be withdrawn from the blockchain.

:vertical_traffic_light: **Why wont it let me send Ether to the ICO?**

You can only purchase a single coin at a time by sending Ether directly, and will only accept a payment of a single Lamborghini at the current price, up to `current price * 110%`. To purchase more at once, please add the interface described above to your wallet interface or use our ~~website~~ (coming soon!).

:fuelpump::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car:
:blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::blue_car::red_car::fuelpump:

### To Do:
- [x] Complete contract
- [x] Alpha test contract (closed)
- [x] Hone pricing scheme
- [ ] Launch contract to MainNet
- [x] JSON files for Admin
- [x] JSON files for User
- [ ] Add Contract source(s) to [Etherscan](https://etherscan.io)
- [ ] Develop webpage
- [ ] Test webpage
- [ ] Launch webpage to server
