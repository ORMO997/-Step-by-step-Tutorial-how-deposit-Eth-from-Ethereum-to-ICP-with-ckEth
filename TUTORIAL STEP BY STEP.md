# -Step-by-step-Tutorial-how-deposit-Eth-from-Ethereum-to-ICP-with-ckEth

To guide you through depositing and withdrawing Ethereum (ETH) between the Ethereum blockchain and Internet Computer (ICP) using Chain Key Ethereum (ckETH), I will break it down into three sections:

Step-by-step tutorial – Detailed instructions for depositing and withdrawing ETH using ckETH.
Basic Frontend – A simple frontend that lets you perform these actions.
Repository Setup – A GitHub repository with working code for reference.
1. Step-by-step Tutorial
Before you begin, you need to be familiar with a few core concepts:

Chain Key Ethereum (ckETH): ckETH is a token representation of ETH on the Internet Computer (ICP). It allows users to bridge ETH from Ethereum to ICP, providing similar value and utility on ICP as ETH does on Ethereum.

ICP Wallet: You’ll need an ICP wallet that supports ckETH, such as Plug Wallet or Stoic Wallet.

MetaMask: A widely used Ethereum wallet that we’ll use for interacting with Ethereum.

Prerequisites
MetaMask Installed: Set up MetaMask with your Ethereum account.
ICP Wallet: Install and set up Plug Wallet or Stoic Wallet for your ICP account.
Node.js and npm: Install Node.js and npm for building the frontend application.
GitHub Account: You'll need a GitHub account to clone the repository and interact with the code.
Step 1: Bridge ETH to ICP
Connect your MetaMask Wallet to the Ethereum Network:

Open MetaMask and ensure you are connected to the Ethereum mainnet.
Obtain ckETH Address:

Get the ckETH contract address on ICP from a service like the Dfinity Foundation or an appropriate bridge service.
Deposit ETH to Bridge:

You will need a specific deposit address for ckETH. You’ll use your ICP wallet (e.g., Plug or Stoic) to find this address under the ckETH section.
In MetaMask, send ETH to this bridge deposit address.
Confirm the Transaction:

Once you confirm the transaction in MetaMask, the bridge will start processing the ETH, and it will be converted into ckETH on the Internet Computer.
The process may take some time depending on Ethereum network conditions.
Check ckETH Balance:

After the transaction is confirmed, ckETH will be credited to your ICP wallet.
You can check the balance within your ICP wallet under the ckETH section.
Step 2: Withdraw ckETH to Ethereum
Withdraw to Ethereum Address:

In your ICP wallet, go to the ckETH section and choose "Withdraw".
Enter your Ethereum address (e.g., MetaMask wallet address).
Initiate the Withdrawal:

Submit the withdrawal transaction, and the ckETH will be sent back to the Ethereum network as native ETH.
Confirmation:

After the transaction processes, you will see the ETH back in your MetaMask wallet.
Step 3: Monitor Transactions and Fees
Keep in mind that there are transaction fees for moving ETH between chains. Ethereum gas fees apply when transferring to ICP and back.
