# ***Daniel Bonfil - 1801214680***

# Voting Decentralized Application 
## Smartcontract on Ethereum BlockChain

## Install Dependencies
* Using Windows 10:
- WLS Ubuntu: https://docs.microsoft.com/en-us/windows/wsl/install-win10
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/
- **Opera: https://www.opera.com/  (There is a problem both with Chrome and Firefox)

## Step 1. Clone Repository
* git clone https://github.com/danybonfil/DanielBonfil_FinalProject_BlockChain

## Step 2. Install NPM Modules
* Using WSL
> [ $ cd /mnt/c/users/ "your directory" ]

> [ $ cd voting_blockchain_final]

> [ $ npm install]

## Step 3. Start Ganache
* Start Ganache and make sure to be connected to "HTTP://127.0.0.1:7545"

## Step 4. Compile & Deploy Election Smart Contract
* Migrate and reset 
> [ $ truffle migrate --reset ]

## Step 5. Configure Metamask
- Connect Metamask with Ganache by using RPC: http://localhost:7545
- Import Ganache account by copying Private Key.

## Step 6. Run the Front End Application
Opera should open local host, otherwise visit: http://localhost:3000
> [ $ npm run dev ]


## Full Tutorial by Dapp University:** https://youtu.be/3681ZYbDSSk
