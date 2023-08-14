
# Biconomy Quickstarter

This Repository is used in the quickstart guide for the [Biconomy SDK](https://docs.biconomy.io/docs/quickstart) as well as the Node JS guides.It contains an example script demonstrating how to set up Biconomy for gasless transactions using the Biconomy Bundler, Smart Account, and Paymaster. This example focuses on initializing the necessary components and creating a Biconomy Smart Account for executing transactions on the Polygon Mumbai network.

## Prerequisites

- Node.js 
- Private Key for the Ethereum Wallet

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Sruthi-Manthena/Quickstart-SCW-Biconomy
   cd Quickstart-SCW-Biconomy
   ```
2. Install Dependecies
   ```bash
   npm install or yarn install 
   ```
3. Create a .env file in the root directory and add your private key
   ```bash
   PRIVATE_KEY="your-private-key-here"
   ```
4. Replace YOUR_BUNDLER_URL and YOUR_PAYMASTER_URL with the actual URLs from your Biconomy account.
5. Run the script
    ```bash
   npm run dev 
   ``` 

## Explanation
`index.js`  This is the main script that initializes the Biconomy Bundler, Smart Account, and Paymaster. It demonstrates how to set up these components and create a Biconomy Smart Account.

`package.json` Contains the project configuration and dependencies.

## Resources

- [Biconomy Documentation](https://docs.biconomy.io/)
- [Biconomy GitHub](https://github.com/bcnmy)

