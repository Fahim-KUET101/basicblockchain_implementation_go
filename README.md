basicblockchain_implementation_go This is a basic blockchain implementation where a genesis block, a new block is created and also used a method to add 
new blocks to the chain. When a genesis block is created then it produced its own block hash. After adding a new block the block data at first transferred into bytes and then using the bytes a HashTransaction function creates new hash value for that block. Here in the NewProofOfWork module creates a new proof of work object for that given block. And a Run method of that funtion performs the proof of work algorithm. I input transaction data manually from code and the output shows the genesis block and the new block with their properties and also each new block saves the previuos hash of the block.
