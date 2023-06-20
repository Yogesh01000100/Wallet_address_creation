# Wallet Address Creation
This is a simple HTML page that allows you to create an Ethereum wallet, fetch the balance of the wallet, and transfer ETH to another address. It utilizes the Web3 library to interact with an Ethereum provider.

## Usage
To use this web application, follow these steps:

- Open the index.html file in a web browser.
- Click the "Create Wallet" button to generate a new wallet address and private key.
- The generated wallet address and private key will be displayed on the page.
- Click the "Fetch Balance" button to retrieve the current balance of the wallet.
- The balance will be displayed on the page.
- To transfer ETH to another address, enter the recipient's address and the amount of ETH to send in the corresponding input fields.
- Click the "Transfer" button to initiate the transaction.
- A transaction confirmation dialog will be shown, displaying the transaction hash, sender address, recipient address, and the amount of ETH transferred.
Note: This web application assumes that you have a local Ethereum provider running on http://localhost:8545, such as Hardhat.

![WhatsApp Image 2023-06-20 at 15 02 54](https://github.com/Yogesh01000100/wallet_address/assets/90953665/bf51ccb8-d527-498e-8c28-dd66331ad0db)

## Dependencies
This application requires the following dependencies:

Web3.js: v1.5.2
The application includes a script tag to load the Web3.js library from the following CDN:

html
Copy code
<script src="https://cdn.jsdelivr.net/npm/web3@1.5.2/dist/web3.min.js"></script>
Development
This code snippet can be used as a starting point for developing an Ethereum wallet application or integrating wallet functionalities into an existing project. You can modify the HTML, CSS, and JavaScript code to fit your specific requirements.

## License
This source code is licensed under the MIT license. Feel free to use and modify it as per your needs.
