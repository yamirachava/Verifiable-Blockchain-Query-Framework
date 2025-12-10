# Verifiable-Blockchain-Query-Framework
A Python-based blockchain prototype enabling verifiable transaction storage and efficient querying using hash chaining, Merkle trees, and freshness, range, and aggregate queries.

This project implements a Python-based prototype for storing, querying, and verifying blockchain-style transactional data. It simulates core blockchain structures such as blocks, hash chaining, and Merkle trees, and supports freshness, search, filtering, and aggregate queries over immutable data.

Objective
- Simulate blockchain data storage with cryptographic integrity guarantees
- Support verifiable data queries including freshness (latest-K), keyword search, and range filters
- Demonstrate tamper detection using hash-based verification mechanisms
- Build an interpretable and executable prototype of blockchain query processing

Data & Methodology
 - Dataset: Synthetic blockchain transaction data generated within the system
 - Tools: Python (hashlib, standard data structures, Jupyter/Colab)
 - Techniques Used:
   - Block and transaction modeling
   - Cryptographic hash chaining for immutability
   - Merkle tree construction for integrity verification
   - Latest-K (freshness) query processing
   - Keyword-based transaction search
   - Range and aggregate query execution
  
Key Insights
- Hash chaining and Merkle roots provide strong tamper-detection guarantees
- Freshness queries can be efficiently supported over append-only ledgers
- Blockchain-style data can be queried without mutating historical records
- Aggregation and filtering remain feasible despite immutability constraints
  
Learning Outcomes
- Gained hands-on understanding of blockchain data structures and integrity mechanisms
- Implemented verifiable query execution over immutable datasets
- Strengthened system design skills by translating distributed-ledger concepts into executable code
- Developed clarity around trade-offs between prototype simulations and full blockchain deployments
