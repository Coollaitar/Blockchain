# Blockchain
### 🔗Notes Taken From LearnWeb3 DAO : https://learnweb3.io/dashboard

<img src="https://i.imgur.com/M9uocHi.png" width="1000" height="550">

| <p align="center"> FRESHMAN🚀 </p> |
| ------ |
| - *Level 1* : Api : It enables two softwares components to communicate with each other using a set of definations or proctols  |
| - *Level 2* : What is Blockhain ? : Permanent Distributed Database shared among multiple nodes on computer network which is impossible to *hack* |
| - Genesis Block : Blockchain start off with a Genesis State |
| - Node : Keeps a copy of global transaction ledger and hence each node can verify and audit transactions happening on the network |
| - Double Spending : Digital Cash scheme in which the same single digital token can be spent more than once |
| - Decentralization : No single authority or middleman , No downtime as the overall network is running across 1000 nodes , Attack Resistant |
| - *Level 3* : What is Web3 ? : Decentralized Internet |
| - Web1 : Read , Web2 : Read-Write , Web3 : Read-Write-Own |
| - What is ETH ? : Ethereum : Decentralized Blockchain |
| - dApps are buit on Ethereum using Solidity Language |
| - Deploy smart contracts on Ethereum Networks |
| -  Ethereum Works on PoW(Proof of Work) but in future it will move on PoS(Proof of Stake) |
| - ETH or Ether : Currency of Ethereum |
| - Smart Contracts : Programmes that are replicated and processes on all the computers on the Ethereum Network |
| - ERC20 Tokens(Smart Contracts) : People can create their own currencies on Ethereum |
| ERC721 and ERC1155 Tokens : Just NFT's and provides requirements to meet when creating NFT's | 
| - Which statement best describes Proof of Work? : Miners compete to solve computational puzzles. The winner of this competition gets to add a block to the blockchain |
| - *Level 4* : Crypto Wallets : Address : Represents your Account address |
| - Private Keys : Just like Password of your Account or Wallet |
| - As your private key is decentralised you don't have an option of forgot password so its important to keep your private key safe and secured |
| - Seed Phrase : Master Password for your Crypto Wallet |
| - Metamask : Ethereum Wallet |
| - *Level 5* : Remix IDE : Used for writing solidity code and testing , debugging and deploying smart contracts |
| - Which of the following environments is NOT supported by Remix? : Solana Testnet |
| - *Level 6* : Solidity : What is Solidity ? : Used to write smart contracts |
| - Runs on Ethereum Virtual Machine (EVM) |
| - Variables and types : Local / State / Global |
| - Local : Declared inside a function and are not stored on blockchain |
| - State : Declared outside function and stored on blockchain |
| - Global : Provides information about the blockchain : Include things like transaction sender , block timestamp, block hash, etc. |
| - Functions,Loops and If/Else |
| - Arrays, String : Memory Variable and Storage Variable can be compared with Ram V/s Hardisk |
| - Build your first dApp with ether.js |
| - Build your own cryptocurrency using ERC-20 tokens |
| - Build your own NFT using ERC-721 token |

<img src="https://i.imgur.com/wPCR9Vn.png" width="1000" height="550">

| <p align="center"> SOPHOMORE🏕️ </p> |
| ------ |
| - *What is Gas ?* : Gas is fuel that allows Ethereum to operate, in the same way that a card needs a gaaoline to run |
| - Gas: General Concepts : Gas unit is used to measure the amount of computational effort required to execute a transaction on Ethereum |
| - Formula : ```gas fees = gas spent* gas price``` (Before London Upgrade) |
| - Gas Spent is total amount of gas that were used to execute the transaction |
| - New Formula : ```gas fees = gas spent * (base fees + priority fees)``` (After London Upgrade) |
| - Variable Block Size : Maximum Block Size Limit is ```30M``` |
| - Better Gas Estimation : minimum ```current base fees * 87.5% ``` Maximum ```current base fees * 112.5%``` |
| - Gas Fees help keep the Ethereum Network secure |
| - *What is Mining ?* : It is the process of creating new blocks of transactions to be added to the Ethereum blockchain network. It also helps keep the network secure from attacks | 
| - *What is Proof of Work ?*(POW) : (Consensus Protocol) Recently on September 15 2022, the Ethereum Merge completed and Ethereum shifted to a Proof of Stake system |
| - *What is Consensus ?* : General Agreement about something (Group Decision) |
| - *Sybil Resistance* : (Basically some hacks done by miners to get more rewards) A Sybil attack is the problem when ine user or group pretends to be many different users |
| - Chain Selection Rules : ```Fork``` means when two miners produces valid blocks roughly at the same time. This can cause different nodes in the network to include different blocks in their blockchain |
| - Bitcoin and Ethereum use the ```Longest Chain``` rule to do prevent the splitting of state |
| - The combination of Longest Chain and Proof of Work rule is known as Nakamoto Consensus |
| - *Finality* : (A transaction has Finality on Ethereum when it's part of a block that can't change) It the time you should wait before considering a transaction irreversible |
| - *The ```Work``` in Proof of Work* : ```HashFunction(dataset, target, nonce, ...) = a number``` |
| - Higher the mining difficulty the lower the target, and hence the harder it is to find a nonce which satisfies this condition |
| - *Ethereum Virtual Machine (EVM)* : Instead of a distributed ledger, Ethereum can be described as a distributed ```state machine```. A state machine is essentially any machine that can change from one state to another in response to certain inputs |
| - *Ethereum State Transition* : Y(S,T) = S^ (S: old valid state, T: new set of valid transactions, S^: new valid state produced) |
| - Advanced Solidity Concepts |

