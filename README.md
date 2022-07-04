# block_chain_ledger
## Using streamlit to demo blockchain technology
### In this class homework we utilized the blockchain technology to keep record of transactions being made. The verification process demonstrates two of the three verification protocols found in a standard blockchain. First, the hash is created which can be verified by rehashing the data after the correct hash is found. If the hash is the same, it is not fraudulent. This data is then kept in a block. Then the program verifies the entire chain to ensure each hash is correct before adding the latest block to the chain.

![image](https://user-images.githubusercontent.com/99841428/177063282-57d66881-f406-4186-882a-7e6e2aac77a2.png)
Above is an image demonstrating the transactions being added to the ledger.

![image](https://user-images.githubusercontent.com/99841428/177063316-0bc98297-659e-48ad-a117-44c28e105c0a.png)
above is an image demonstrating the program verifying the ledger is accurate.

### The only missing verification step would be for the full nodes of the blockchain to verify that the transaction took place and that the wallet of the sender has sufficient funds for the transaction.
