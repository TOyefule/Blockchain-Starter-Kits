# Blockchain-Starter-Kits
Starter Apps - Well Documented - Easy to Deploy

This is a list of SIMPLE, well-supported blockchian based apps. 

Each Starter Kit Should Include:

1. Description of app and support/forum info
2. Link to Code Bases/Source Codes
3. Deployment Instructions
4. Demo of running app



EOSIO
  https://github.com/EOSIO/eosio-project-boilerplate-simple
    Boiler Plate App - NoteChain
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
