# LamboCoins
## The Ferrari of Altcoins - An ultra-limited supply collector's edition coin for the astute crypto-wizard

### Closing Date
Subject to change depending on demand. Check back here for the most up to date information
```
1st April, 2018
```

### Whats this project all about?
- Ultra limited edition, only 250 coins released publicly!
- the ORIGINAL collector coin
- 6 coins are retained for the developers (< 2.5% of all Lambos)
- 256 total Lambos spawned
- Lambos are distributed amongst the accounts at the end of the ICO who have sent the most Ether
- Make sure your balance is above the CurrentPrice at the end of the ICO to get your Lambo(s). Don't miss out!!
- send Ether straight to the contract address, it's that easy!
- LamboCoin is an unowned ERC20 compliant contract, it will never selfdestruct and you can trade it as you wish!

### What's the details?
- ICO
  - Contract Address (Rinkeby TestNet):

  `0xe81bf7c7f25410931c26ad91cA1b5cdD5DDa4C22`

  Send Ether to this address to be in the running to win those LamboCoins!
  
  - JSON Interface; copy the code below to your preferred wallet interface to see your current standing
  ```
  [ { "constant": true, "inputs": [ { "name": "you", "type": "address" } ], "name": "userStatistics", "outputs": [ { "name": "amount", "type": "uint256", "value": "0" }, { "name": "lambos", "type": "uint256", "value": "0" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "LamboContractAddress", "outputs": [ { "name": "", "type": "address", "value": "0xde22f96b0ed0c3a906b70cedccbbf259df294359" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "currentLamboPrice", "outputs": [ { "name": "Gwei", "type": "uint256", "value": "0" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": false, "inputs": [], "name": "endICO", "outputs": [], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": true, "inputs": [], "name": "investors", "outputs": [ { "name": "", "type": "uint256", "value": "0" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "owner", "outputs": [ { "name": "", "type": "address", "value": "0xfd8d1160459e17a9d7ec2c62340760e24a5f75ab" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "inputs": [], "payable": false, "stateMutability": "nonpayable", "type": "constructor" }, { "payable": true, "stateMutability": "payable", "type": "fallback" }, { "anonymous": false, "inputs": [ { "indexed": false, "name": "who", "type": "address" }, { "indexed": false, "name": "userNumber", "type": "uint256" } ], "name": "newInvestor", "type": "event" }, { "anonymous": false, "inputs": [ { "indexed": false, "name": "who", "type": "address" }, { "indexed": false, "name": "howMuch", "type": "uint256" } ], "name": "valueAdded", "type": "event" } ]
  ```

- LamboCoin
  - Contract Address (Rinkeby TestNet):

  `0xdE22f96b0Ed0C3a906B70cEDCCBbf259dF294359`

  add this address to your wallet interface to view your coins upon distribution

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

The first car any cryptomillionaire must buy is obviously a Lamborghini, so logically the original ultra rare coin should be based on them

- **Why only 256 coins?**

For Exclusivity, Like a real Lamborghini each coin is exclusive and made in limited numbers. This IGO is the only IGO that will occur meaning you will be one of the elite few who can have the privelege of owning one (or many, depending on how much Ether you have)

- **How do I get them?**

Just send Ether to the contract address, coins will be distributed to the highest bidders such that the lowest bid, when applied to these highest bidders, will distribute no more than 250 coins to them

- **If I dont get any coins will I get my money back?**

No, it's a risk you must be willing to take. No one said ultra-exclusivity would be cheap.

### To Do:
- [x] Write Contract
- [x] Test Contract
- [ ] Trim JSON
- [ ] Release to MainNet
- [ ] Develop frontpage
