# Verifica

This application is a decentralized platform that allows for the tracking of a product's supply chain journey. Utilizing the Ethereum blockchain and smart contracts, it ensures transparency and immutability throughout the product's journey. Furthermore, it incorporates an anti-counterfeiting system and QR code scanning feature to enhance product authenticity and traceability.


## Architecture
![web3app](https://user-images.githubusercontent.com/98258627/215092397-a134ff74-dc92-424f-af32-03457f1e2c54.jpg)




## Prerequisites

1.  [Ganache](https://www.trufflesuite.com/ganache)
2.  [Xampserver on Windows](https://www.apachefriends.org/download.html) or [MAMP on MacOS X](https://www.mamp.info/en/windows/)
3.  [Google Chrome](https://www.google.com/chrome/) and [Metamask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)

## Instructions

1.  Download and install Ganache, Xampserver/MAMP, and Google Chrome.
2.  Create a Metamask account.
3.  Run Ganache and set up a custom RPC in Metamask with the RPC Server URL from Ganache.
4.  Import an account from Ganache into Metamask using the private key.
5.  Copy the `smartcontract.sol` file from this repo and paste it into [Remix](https://remix.ethereum.org/).
6.  Compile and deploy the smart contract on the `Injected Web3` environment in Remix.
7.  Copy the contract address and ABI from Remix and paste them into the `app.js` file.
8.  Start Xampserver/MAMP and move the project folder into the `htdocs` directory.
9.  Go to `localhost` or `localhost:8888` and import the SQL queries provided in the `sql` folder using phpmyadmin.
10.  Open `http://localhost:8888/Verifica` or `http://localhost/Verifica` (URL may vary depending on software and OS) to run the application.


## Features

-   Track the supply chain from raw material sourcing to delivery to the customer
-   Verify product authenticity using QR code scanning
-   Transparent and tamper-proof record keeping on the blockchain
-   Secure and decentralized storage of data
-   Traceability for products and their history

## UI
![Adding_Product (Metamask)](https://user-images.githubusercontent.com/98258627/215092472-8aa556a7-961a-436e-b6d1-472ba1ff1a40.png)

![Product_ID_1](https://user-images.githubusercontent.com/98258627/215092516-9871cf0f-1c84-4c0a-87b3-cdcdbd45d780.png)


