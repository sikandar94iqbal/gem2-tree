# gem2-tree

"Gem2Tree" is a gas-efficient data structure proposed for authenticated range queries in blockchain systems. It was introduced in a research paper titled "Gem2Tree: A Gas-Efficient Structure for Authenticated Range Queries in Blockchain" by Jing Chen, Jiapeng Zhang, Zibin Zheng, and Qianhong Wu.

Gem2Tree is designed to improve the efficiency and security of range queries in blockchain systems. Range queries refer to queries that request all data within a specific range, such as finding all transactions within a certain time period. In a blockchain system, range queries can be used to retrieve information such as transaction history or user account balances.

The Gem2Tree data structure is built on top of a Merkle tree, which is a hash tree used for data verification in blockchain systems. Gem2Tree enhances the Merkle tree with additional nodes and links to improve its efficiency for range queries. Specifically, Gem2Tree introduces a new type of node called the "gap node," which represents a range of missing nodes in the tree. By using gap nodes, Gem2Tree reduces the number of nodes that need to be verified during range queries, which reduces the gas cost of the queries.

Gem2Tree also includes a proof system that enables users to verify the authenticity of the range query results without needing to download the entire tree. This proof system further reduces the gas cost of range queries and improves the scalability of blockchain systems.

Overall, Gem2Tree is a promising data structure for improving the efficiency and security of range queries in blockchain systems. However, it is still a relatively new proposal, and further research and development are needed to fully evaluate
