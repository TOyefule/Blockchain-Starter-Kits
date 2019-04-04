# Blockchain-Starter-Kits
Starter Apps - Well Documented - Easy to Deploy

This is a list of SIMPLE, well-supported blockchian based apps. 

Each Starter Kit Should Include:

1. Description of app and support/forum info
2. Link to Code Bases/Source Codes
3. Deployment Instructions
4. Demo of running app




HYPERLEDGER SUPPLY CHAIN APP

https://github.com/IBM/blockchainbean2


This code pattern shows how to model a supply-chain network using the IBM Blockchain Platform V2 Beta and is based on a collaboration with Brooklyn Roasting Company. The story, along with the supply-chain documents that were used to model this network, can be found at: https://www.ibm.com/blockchainbean







***EOSIO - NOTE TAKING APP***

  https://github.com/EOSIO/eosio-project-boilerplate-simple
        
    
    NoteChain demonstrates the eosio platform running a blockchain as a local single node test net with a simple DApp, NoteChain. NoteChain allows users to create and update notes. This guide uses scripts, containing relevant commands, which will show you how to install, build and run NoteChain, and by doing so will demonstrate:

    Downloading and running eosio in docker;
    Managing your docker container;
    Setting up and running a local single node testnet;
    Setting up wallets, keys, and accounts;
    Writing and deploying a smart contract;
    Implementing a web based UI using React;
    Connecting the UI to the blockchain using eosjs;
    Styling the UI using Material-UI.

Github eosio-project-boilerplate-simple (https://github.com/EOSIO/eosio-project-boilerplate-simple) contains the UI and Smart Contract code, as well as setup scripts which will initialise and start all the necessary components.

The sample DApp demonstrates storing data in multi index table and retrieving this data into the web based UI. NoteChain is a simple note taking application, where notes are tied to user accounts. For this example, all accounts are pre-created by scripts and the account details are displayed at the bottom of the NoteChain UI.

Each account can then be used to add a note to the blockchain. The individual notes are saved in a multi-index table and for simplicity are of fixed width. Each account may have one note attached to it, adding a note to an account with an existing note will replace the existing note with a new note.






***EOSIO - BLOG APP***

https://github.com/EOSIO/eosio-project-demux-example


This Blog DApp demonstrates the eosio platform running a blockchain as a local single node test net with a simple DApp. This DApp allows users to create, edit, delete and like blog posts. This guide uses scripts, containing relevant commands, which will show you how to install, build and run the DApp, and by doing so will demonstrate:

    Downloading and running eosio in docker
    Managing your docker container
    Setting up and running a local single node testnet
    Setting up wallets, keys, and accounts
    Writing and deploying a smart contract
    Implementing a Node.js server with Demux to watch and read the state of the blockchain
    Setting up and using a MongoDB database to store state data relevant to the DApp
    Implementing a web based UI using React bootstrapped with Create React App
    Connecting the UI to the blockchain using eosjs





***HYPERLEDGER - INSURANCE APP***

https://github.com/IBM/build-blockchain-insurance-app

This project showcases the use of blockchain in insurance domain for claim processing. In this application, we have four participants, namely insurance, police, repair shop and shop peer. Insurance peer is the insurance company providing the insurance for the products and it is responsible for processing the claims. Police peer is responsible for verifying the theft claims. Repair shop peer is responsible for repairs of the product while shop peer sells the products to consumer.

Audience level : Intermediate Developers
Included Components

    Hyperledger Fabric
    Docker

Application Workflow Diagram

Workflow

    Generate Certificates for peers
    Build Docker images for network
    Start the insurance network
