Fake Product Identification using Blockchain

- Truffle v5.6.7 (core: 5.6.7)
- Ganache v7.5.0
- Solidity v0.5.16 (solc-js)
- Node v15.8.0
- Web3.js v1.7.4
- npm 7.5.1

1.  Chrome 
2. Metamask browser extension
    
4. Open Ganache, (to setup local blockchain)
    - crerate new workspace
    - add truffle-config.js  in truffle project 
    - change port to 7545 in server settings (same as port in truffle-config.js)
5. In chrome, open metamask 
   - add new test network using  
        - NETWORK ID (i.e. 5777 ,from Ganache Server settings) 
        - RPC SERVER (i.e HTTP://127.0.0.1:8545 ,from Ganache Server settings)
        - CHAIN CODE (i.e. 1337)
   - import account using private key of any account from local blockchain available in Ganache.
6. In terminal, run following commands:-
- Run migrations to deploy contracts.
truffle migrate

- To start a server and it will open a homepage (index.html) file in the default browser.

npm run dev 

7. Login to metamask ,and connect the added account to local blockchain (i.e.localhost:3000)
8. Interact with website
