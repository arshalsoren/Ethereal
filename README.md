# What is Ethereal?
- A cryptocurrency made for the python-based blockchain.
- Send and Receive Ethereal(cryptocurrency).

## To be installed:
- Flask==0.12.2: pip install Flask==0.12.2
- [Postman](https://www.getpostman.com/)
- requests==2.18.4: pip install requests==2.18.4

## How does it work?
- <b>Genesis Block</b>: The first block of the Ethereal Blockchain.
![genesis_block(0).png](https://github.com/arshalsoren/Ethereal/blob/main/images/genesis_block(0).png)

- <b>connect_node</b>: Establishes connection between nodes. Uses [nodes.json](https://github.com/arshalsoren/Ethereal/blob/main/nodes.json) file for node's address.
![connect_node(1).png](https://github.com/arshalsoren/Ethereal/blob/main/images/connect_node(1).png)

- <b>mine_block</b>: Mines a new block and adds it to the current blockchain.
![mine_block(2).png](https://github.com/arshalsoren/Ethereal/blob/main/images/mine_block(2).png)

- <b>replace_chain</b>: Changes the existing version of the blockchain present on that individual's node to the longest version of the blockchain. 
![replace_chain(3).png](https://github.com/arshalsoren/Ethereal/blob/main/images/replace_chain(3).png)

- <b>add_transaction</b>: Sending 100 Ethereal from "Arshal" to "Nuna". Using [transaction.json](https://github.com/arshalsoren/Ethereal/blob/main/transaction.json).
![add_trans(4).png](https://github.com/arshalsoren/Ethereal/blob/main/images/add_trans(4).png)

- As you can see, A new block is added to the current blockchain and the transaction is added to the 3rd block.
![new_block_added(5).png](https://github.com/arshalsoren/Ethereal/blob/main/images/new_block_added(5).png)

- Now sending 10000 Ethereal from "Arshal" to "Soren". Using [transaction.json](https://github.com/arshalsoren/Ethereal/blob/main/transaction.json).
![to_soren(6).png](https://github.com/arshalsoren/Ethereal/blob/main/images/to_soren(6).png)

- <b>Final Ethereal Blockchain</b>
![new_chain(7).png](https://github.com/arshalsoren/Ethereal/blob/main/images/new_chain(7).png)
