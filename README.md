# Simple BlockChain and Create Cypto Currency

This repo contains two small projects to better understand how blockchain works

## Simple Blockchain

Create a simple blockchain that can mine a block, check if the chain is valid and get the current full chain.

### How to use it

```sh
cd simple_blockchain

python blockchain.py
```

### Make Requests

Open up a browser, go to the following url to perform actions

MineBlock: http://localhost:5000/mine_block  
Get the full chain: http://localhost:5000/get_chain  
Check if the chain is valid: http://localhost:5000/is_valid  

## Create Crypto Currency

Create a simple crypto currency with multiple nodes

### How to use it

```sh
cd create_cypto_currency

python node_5001.py
python node_5002.py
python node_5003.py

```
### Make Requests

Open up a browser, go to the following url to perform actions on the nodes. The nodes are hosted on port 5001, 5002, 5003

MineBlock: http://localhost:5001/mine_block   
Get the full chain: http://localhost:5001/get_chain   
Check if the chain is valid: http://localhost:5001/is_valid  
Add Transactions: http://localhost:5001/add_transaction  
Connect Node: http://localhost:5001/connect_node  
Replace Chain: http://localhost:5001/  
  

