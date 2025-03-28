<h1>Blockchain Transaction Analysis in Azure Databricks</h1>

Detecting Suspicious Activity in a Simulated Crypto Network

<h2>Project Overview</h2>
This project simulates and analyses blockchain transaction data to detect suspicious patterns, such as illicit activity, mixer usage, and high-risk address clusters. Using Databricks and Spark SQL, I investigate entity behaviour, transaction flows, and potential money laundering tactics mimicking the investigative techniques used in blockchain forensics.

<h2>Tech Stack:</h2>

- Azure Databricks (Cloud-Based Analytics)
- Apache Spark (Big Data Processing)
- SQL / PySpark (Querying & Analysis)

<h2>Data Simulation</h2>

Since real blockchain data is restricted, I generated 20,000 synthetic transactions with the following attributes:

- From / To Addresses: Simulated wallet addresses
- Entity Types: exchange, individual, marketplace, illicit, unknown
- Transaction Amounts: Randomized with real-world distribution patterns
- Mixers: Flagged transactions passing through mixing services
- Clusters: Related addresses grouped under a common cluster_id
- Illicit Activity Labels: Based on entity type and mixer usage

<h2>Key Analysis</h2>

- Exploratory Data Analysis (EDA): Distribution of transaction amounts & entity types
- Mixer activity trends
- High-frequency transaction detection
- Suspicious Behavior Detection
- Clusters with high % of illicit transactions
- Circular transactions (funds looping through wallets)
- Time-Series Insights: Illicit activity trends over time
- Daily transaction volume analysis

<h2>Why This Matters</h2>
This project showcases skills in big data processing, financial crime detection, and blockchain analytics—key areas for roles at Chainalysis and similar firms. By applying real-world forensic techniques to synthetic blockchain data, this portfolio piece demonstrates how data analytics can uncover financial crime patterns in cryptocurrency networks.
