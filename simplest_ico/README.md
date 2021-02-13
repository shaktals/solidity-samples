# Solidity smart contract samples

## To run it:

1) Run Truffle Ganache (https://www.trufflesuite.com/ganache) locally
2) Run the etherwallet-v3.40.0 web page (e.g.: by double clicking on it's _index.html_)
3) Connect the web page to *Ganache* server, by choosing *Add Custom Network / Node* on top right corner of the page
4) Go to the _Contracts_ menu, click on _Deploy Contract_,
5) Choose a solidity IDE, https://remix.ethereum.org is the simplest option
6) Compile the code in _hadcoin_ico.sol_ in it, using a compiler version compatible with _pragma solidity ^0.4.11_
7) Get the ABI code from the compiler, and paste the value of it's _object_ key on the etherwallet web page _Byte Code_ field
8) On the page, choose _Private key_ as means of connecting to a wallet, get the private key from any of *Ganache* fake wallets and paste it on the field
9) Click on _Unlock_ to connect to the wallet, then on _Sign Transaction_ and then on _Deploy Contract_ and then confirm
10) You can check the _Transactions_ list on *Ganache* to confirm it's there

## To interact with it:

1) Go to _Contracts_, then _Interact with contract_ on the etherwallet web page
2) Get the contract address from *Ganache*, and paste it on the web page field
3) Get the _ABI code_ from the solidity compiler (used to compile _hadcoin_ico.sol_) and paste it on the respective field
4) Click on _Access_, and you can now interact with the 7 self explanatory functions available
