# LamboCoins
## The Ferrari of Altcoins - An ultra-limited supply collector's edition coin for the astute crypto-wizard

### Closing Date
```
When all Lamborghinis are sold!
```

### Whats this project all about?
- Ultra limited edition, only 250 Lamborghinis released publicly!
- the ORIGINAL collector coin!
- 6 coins are retained for the developers (< 2.5% of all Lamborghinis, we're not greedy).
- 256 total Lamborghinis.
- Lamborghinis are distributed first come, first serve.
- Lamborghinis are tradable as soon as you buy them!
- each successive lamborghini is cost `price * interest rate` more. Don't miss out!!
- Ether sent to ICO contract will only allow purchase of 1 Lamborghini at a time.
- Ensure you withdraw all your remaining funds. The ICO will end approximately 1 week after the last Lamborghini is sold.
- LamboCoin is an unowned ERC20 compliant contract, it will never selfdestruct and you can trade it as you wish!

### What's the details?
- ICO
  - Contract Address (Rinkeby TestNet):

  `none currently`
  
  See it on [Etherscan](https://rinkeby.etherscan.io/address/?)

  Send Ether to this address to be in the running to win those LamboCoins!
  
  - JSON Interface; copy the code below to your preferred wallet interface to see your current standing
  ```
  awaiting update
  ```

- LamboCoin
  - Contract Address (Rinkeby TestNet):

  `none currently`
  
  See it on [Etherscan](https://rinkeby.etherscan.io/address/?) 
  
  _Note: LamboCoin manages the ICO in a separate contract_
  
  Add this address to your wallet interface to tranfer your coins

  - JSON Interface; copy the code below to your preferred wallet interface to access the trade functions
  ```
  [ 
    { 
      "constant": true, 
      "inputs": [], 
      "name": "name", 
      "outputs": [ { "name": "", "type": "string", "value": "LamboCoin" } ], 
      "payable": false, 
      "stateMutability": "view", 
      "type": "function" 
    }, { 
      "constant": false, 
      "inputs": [ { "name": "_spender", "type": "address" }, 
                  { "name": "_value", "type": "uint256" } ], 
      "name": "approve", 
      "outputs": [ { "name": "success", "type": "bool" } ], 
      "payable": false, 
      "stateMutability": "nonpayable", 
      "type": "function" 
    }, { 
      "constant": true, 
      "inputs": [], 
      "name": "totalSupply", 
      "outputs": [ { "name": "", "type": "uint256", "value": "256" } ], 
      "payable": false, 
      "stateMutability": "view", 
      "type": "function" 
    }, { 
      "constant": false, 
      "inputs": [], 
      "name": "killContract", 
      "outputs": [], 
      "payable": false, 
      "stateMutability": "nonpayable", 
      "type": "function" 
    }, { 
      "constant": false, 
      "inputs": [ { "name": "_from", "type": "address" }, 
                  { "name": "_to", "type": "address" }, 
                  { "name": "_amount", "type": "uint256" } ], 
      "name": "transferFrom", 
      "outputs": [ { "name": "success", "type": "bool" } ], 
      "payable": false, 
      "stateMutability": "nonpayable", 
      "type": "function" 
    }, { 
      "constant": true, 
      "inputs": [], 
      "name": "decimals", 
      "outputs": [ { "name": "", "type": "uint256", "value": "0" } ], 
      "payable": false, "stateMutability": "view", "type": "function" 
    }, { 
      "constant": false, 
      "inputs": [], 
      "name": "completeDistribution", 
      "outputs": [ { "name": "", "type": "bool" } ], 
      "payable": false, 
      "stateMutability": "nonpayable", 
      "type": "function" 
    }, { 
      "constant": false, 
      "inputs": [], 
      "name": "withdraw", 
      "outputs": [], 
      "payable": false, 
      "stateMutability": "nonpayable", 
      "type": "function" 
    }, { 
      "constant": true, 
      "inputs": [ { "name": "_owner", "type": "address" } ], 
      "name": "balanceOf", 
      "outputs": [ { "name": "", "type": "uint256", "value": "0" } ], 
      "payable": false, 
      "stateMutability": "view", 
      "type": "function" 
    }, { 
      "constant": true, 
      "inputs": [], 
      "name": "symbol", 
      "outputs": [ { "name": "", "type": "string", "value": "Lamborghini" } ], 
      "payable": false, 
      "stateMutability": "view", 
      "type": "function" 
    }, { 
      "constant": false, 
      "inputs": [ { "name": "_to", "type": "address" }, 
                  { "name": "_amount", "type": "uint256" } ], 
      "name": "transfer", 
      "outputs": [ { "name": "success", "type": "bool" } ], 
      "payable": false, 
      "stateMutability": "nonpayable", "type": "function" 
    }, { 
      "constant": true, 
      "inputs": [ { "name": "tokenAddress", "type": "address" }, 
                  { "name": "who", "type": "address" } ], 
      "name": "getTokenBalance", 
      "outputs": [ { "name": "", "type": "uint256", "value": "0" } ], 
      "payable": false, 
      "stateMutability": "view", 
      "type": "function" 
    }, { 
      "constant": true, 
      "inputs": [ { "name": "_owner", "type": "address" }, 
                  { "name": "_spender", "type": "address" } ], 
      "name": "allowance", 
      "outputs": [ { "name": "", "type": "uint256", "value": "0" } ], 
      "payable": false, "stateMutability": "view", "type": "function" 
    }, { 
      "constant": false, 
      "inputs": [ { "name": "_tokenContract", "type": "address" } ], 
      "name": "withdrawForeignTokens", 
      "outputs": [ { "name": "", "type": "bool" } ], 
      "payable": false, 
      "stateMutability": "nonpayable", 
      "type": "function" 
    }, { 
      "constant": false, 
      "inputs": [ { "name": "newOwner", "type": "address" } ], 
      "name": "transferOwnership", 
      "outputs": [], 
      "payable": false, 
      "stateMutability": "nonpayable", 
      "type": "function" 
    }, { 
      "constant": false, 
      "inputs": [ { "name": "_to", "type": "address" }, 
                  { "name": "_amount", "type": "uint256" } ], 
      "name": "distribute", 
      "outputs": [ { "name": "", "type": "bool" } ], 
      "payable": false, 
      "stateMutability": "nonpayable", 
      "type": "function" 
    }, { 
      "inputs": [ { "name": "_totalSupply", 
                    "type": "uint256", 
                    "index": 0, 
                    "typeShort": "uint", 
                    "bits": "256", 
                    "displayName": "&thinsp;<span class=\"punctuation\">_</span>&thinsp;total Supply", 
                    "template": "elements_input_uint", 
                    "value": "256" } ], 
      "payable": false, 
      "stateMutability": "nonpayable", 
      "type": "constructor" 
    }, { 
      "payable": true, 
      "stateMutability": "payable", 
      "type": "fallback" 
    }, { 
      "anonymous": false, 
      "inputs": [ { "indexed": true, 
                    "name": "_from", 
                    "type": "address" 
                  }, { 
                    "indexed": true, 
                    "name": "_to", 
                    "type": "address" 
                  }, { 
                    "indexed": false, 
                    "name": "_value", 
                    "type": "uint256" 
                  } ], 
      "name": "Transfer", 
      "type": "event" 
    }, { 
      "anonymous": false, 
      "inputs": [ { "indexed": true, 
                    "name": "_owner", 
                    "type": "address" 
                  }, { 
                    "indexed": true, 
                    "name": "_spender", 
                    "type": "address" 
                  }, { 
                    "indexed": false, 
                    "name": "_value", 
                    "type": "uint256" } ], 
      "name": "Approval", 
      "type": "event" 
    } 
  ]
  ```

### FAQ
- **Why Lamborghini?**

The first car any cryptomillionaire must buy is obviously a Lamborghini, so logically the original ultra rare coin should be based on them.

- **Why only 256 coins?**

For Exclusivity, Like a real Lamborghini each coin is exclusive and made in limited numbers. This IGO is the only IGO that will occur meaning you will be one of the elite few who can have the privelege of owning one (or many, depending on how much Ether you have). 256 was chosen because it is equal to 2^8, it's an awesome number.

- **How do I get them?**

Add the contract above to your ethereum client. Website coming soon!

- **If I dont get any coins will I get my Ether back?**

You may withdraw funds up until the ICO contract is finished. After this time any remaining funds can no longer be refunded.

### To Do:
- [x] Write Contract
- [x] Test Contract
- [ ] Add Contract source to [Etherscan](https://etherscan.io)
- [ ] Trim JSON
- [ ] Release to MainNet
- [ ] Develop Front-end for users
