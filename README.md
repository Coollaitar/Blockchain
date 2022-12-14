# Blockchain <img src="https://media.tenor.com/UTxZPwKlNNIAAAAi/ethereum-ethereum-crypto.gif" width="60" height="60" />
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
| - **Advanced Solidity Concepts 👉** |
| - 1. Mappings : Mappings are created with syntax ```mapping (keyType => valueType)``` |
| - Mappings are used to store data in key-value pairs |
| - We can also create nested mappings, where the `key` points to a secomd nested mapping. |
| - For eg: ```mapping(address => mapping(unit => bool)) public nestedMap``` |
| - 2. Enums : Enums stands for Enumerable. They are commonly used to restrict a variable to only have one of a few predefined values. They are internally represented as `uint` |
| - 3. Structs : Used to create custom `datatypes` |
| - 4. View and Pure Functions : Getter Functions (those which return values) can be declared either `view` or `pure` |
| - Difference between View and Pure is that View promises not to modify the state but can read state whereas Pure promises not to modify or read from state | 
| - 5. Function Modifiers : Commonly used for restricting access to certain functions, protecting against certain types of attacks,etc. |
| - Eg: To check whether the function caller is owner or not we can declare a modifier(`owner=msg.sender`) and just add it after`()` the name of modifier |
| - 6. Events : Events allows contracts to perform logging on the Ethereum blockchain. Logs for a given contract can be parsed later to perform updates on the frontend interface. |
| - Commonly used to allowed frontend interfaces to listen for specific events and update the user interface or used as `cheap form of storage` |
| - 7. Constructors : Optional Function : Also pass arguements to constructors | 
| - 8. Inheritance : Contracts can `inherit` other contract by using `is` keyword | 
| - **IMPORTANT** : 1. A parent contract which has a function that can be overridden by a child contract muste be declared as a `virtual` function |
| - **IMPORTANT** : 2. A child contract that is going to override a parent function must use the `override` keyword |
| - `super.foo()` if the function name is foo() and it is inherited for eg:`contract E is C,B {function foo () public pure override (C,B) returns (string memory) {return super.foo();}}` this will return the `Right-Most parent with function foo();` |
| - 9. Transferring ETH : **Recommended Way** : To transfer ETH from a contract is to use the `call` function. The `call` function return `bool` indicating success or failure of transfer |  
| - **How to receive Ether in a contract ?** |
| - 1. `recieve() external payable` `recieve` is called if `msg.data` is an empty value otherwise `fallback` is used |
| - 2. `fallback() external payable` | 
| - 10. Calling External Contracts : For eg: `import "./Foo.sol";` |
| - 11. Solidity Libraries : Libraries cannot contain any `state` variables, and cannot transfer ETH | 
| - **Providers, Signers, ABIs, and Approval Flows** |
| -  **Providers and Signers** : 1. A `Provider` is an Ethereum node connection that allows you to read data from its `state`. You will use a `provider` to do things like calling read-only functions in smart contracts, fetching `balances` of accounts, fetching transaction details, etc | 
| - 2. A `Signer` is an Ethereum node connection that allows you to write data to the blockchain. Use a `Signer` for calling `write` functions in smart contracts, transferring ETH between accounts,etc. |
| `Signer` *Example* : When a dApp attempts to send a transaction to the blockchain, the Metamask window pops up asking the user to confirm the action. | 
| - **BigNumbers** : `BigNumber` is a custom class library, written in Javascript, that introduces it's own functions for mathematical functions - `BigNumber` has a significantly larger capacity for numbers than what Javascript can natively support |
| - When we are working with `BigNumber` we need to use it's mathematical functions like `.add()`, `.mul()` |
| - **ABI (Application Binary Interfaces)** :  `ABI` contains `rules and metadata` about functions present in contract, which help in doing the proper data conversion back and forth | 
| - **ERC20 Approval Flow** : Safer way to pull tokens out of someones's account |
| - `approve(address spender , uint256 amount)` This allows user to `approve` a different address to spend up to `amount` tokens on their behalf. i.e This function provides an *Allowance* to the `spender` of up to `amount` |
| - **Please Read the Example Provided by LearnWeb3DAO to clear the concept more** |
| - keccak256->hash->uint->%100->random numbers |




