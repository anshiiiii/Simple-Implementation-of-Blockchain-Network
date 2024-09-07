# Simple-Implementation-of-Blockchain-Network
This project implements a basic blockchain system with a web-based frontend using Python Flask App. It allows users to create transactions, mine new blocks, and synchronize with other nodes in the network. The system demonstrates core blockchain concepts such as proof-of-work, transaction verification, chain validation and conflict resolve mechanisms.

## Features

- Generate Wallet to make transactions(public and private keys)
- Create and verify transactions
- Add and synchronize with other blockchain nodes
- Mine new blocks
- Sync blockchain with other nodes in the network
- Web interface for easy interaction

## Technologies Used

- Backend: Python, Flask
- Frontend: HTML, JavaScript, Bootstrap
- Cryptography: pycryptodome.

## Setup

### Prerequisites

- Python 3.6+
- pip
- Install pycryptodome using pip
- Install other imports like flask, flask-cors
- use python virtual environment to avoid package conflicts

### Installation

- Clone the repository to your local machine and setup the environment with prerequisites mentioned above.

### Running the Application

- Navigate to blockchain_client folder(Blockchain Client):
  - Run the command "python blockchain_client.py" in your terminal.
  - Your interface for generating wallet and making transactions is ready.
  - while making transaction you can choose to which node(5000 or 5001) in the network to post your transaction.

- Navigate to blockchain folder to run the mining network(Blockchain Frontend):
  - Run the command "python blockchain.py -p 5000" in your terminal to add node running in the port 5000.
  - Run the command "python blockchain.py -p 5001" in your terminal to add node running in the port 5001.
  - This step tells us about the multiple nodes(participants/miners) present in the network.
  - Refresh the tranactions tab to see any new transactions are made and mine them

- Go to configure in navigation bar of Blockchain Frontend to add the other nodes(participants/miners) in the network and keep syncing the chain woth them.


## [Refer to this blog for theoretical explaination of this implementation](https://adilmoujahid.com/posts/2018/03/intro-blockchain-bitcoin-python/)
