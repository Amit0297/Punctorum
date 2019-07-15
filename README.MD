The application needs a Reddis server or Pub nub for Publisher Subscriber model implementation.

Steps to start in production:
Install node.js, git, Reddis
start the service using npm start
by default it will listen on localhost:3000

Front-end:
on the index page there will be an address(public key) of the wallet and defaultbalance(1000).
The links are as follows:
1.Blocks: Blocks after being mined by peers and added to the Blockchain.
2. Conduct a transaction: For a transaction to occur, reciver's public key and amount should be entered.
3.Transaction pool: A pool where transactions lie before they are added to the Blockchain.
There are two parts of a transaction
1. The part which tells us about the sender wallet; amount and address.
2. The part which gives the remaining balance to our own wallet.

There is an option of mine transaction in transaction pool, which is used to mine and add transactions to the blockchain.

To add a peer to the network, clone the same code with just one change on a different machine 
In index.js change const ROOT_NODE_ADDRESS to the public address on which the first instance is running.

For any further details:
Contact: amit581h@gmail.com