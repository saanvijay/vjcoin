# vjcoin
Develop, deploy and make transaction your own cryptocurrency

# Pre-requisites
    1. Remix IDE (remix.ethereum.org)
    2. Solidity (version 0.4.24 and above)
    3. Cryptocurrency Wallet (eg: MetaMask)

# Steps to be followed (Compile and Deployment)
    1. Write your contract using solidity and upload it in remix 
    ![alt text] (https://github.com/saanvijay/vjcoin/blob/main/images/upload%20contract.png)
    
    2. Compile your contract using remix
    ![alt text] (https://github.com/saanvijay/vjcoin/blob/main/images/compile%20contract.png)

    3. Connect MetaMask wallet (You can use any crypto wallet), since this is a demo, I have connected my wallet to "Rinkeby Test Network". Make sure you have Ether in your account, if not, connect to https://faucet.rinkeby.io/ and give your Public key, you will get ether for testing.
    ![alt text] (https://github.com/saanvijay/vjcoin/blob/main/images/connect%20metamask.png)

    4. Deploy Contract using MetaMask
    ![alt text] (https://github.com/saanvijay/vjcoin/blob/main/images/deploy%20contract.png)
    ![alt text] (https://github.com/saanvijay/vjcoin/blob/main/images/deploy%20contract%20using%20metamask.png)

    5. For successful deployment, you can get valid transaction id, check the log window
    ![alt text] (https://github.com/saanvijay/vjcoin/blob/main/images/successful%20deployment.png)

    6. You can check the etherscan for successful transaction
    ![alt text] (https://github.com/saanvijay/vjcoin/blob/main/images/check%20with%20etherscan.png)

# Steps to be followed to transfer new coin to other accounts
    1. Make sure you have connected your Matamask wallet with Rinkeby test network
    2. Using Metamask wallet, transfer new coin to other account
        ![alt text] (https://github.com/saanvijay/vjcoin/blob/main/images/transfer%20coin%20to%20coinbase.png)
    3. Confirm transaction
        ![alt text] (https://github.com/saanvijay/vjcoin/blob/main/images/transfer%20coin%20confirm.png)
    4. Successful transfer 
        ![alt text] (https://github.com/saanvijay/vjcoin/blob/main/images/successful%20transfer.png)
    5. You can see your balance of coins in your wallet by adding token, (make sure you have token contract address which you deployed)
        ![alt texr] (https://github.com/saanvijay/vjcoin/blob/main/images/Add%20new%20token%20to%20metamask.png)