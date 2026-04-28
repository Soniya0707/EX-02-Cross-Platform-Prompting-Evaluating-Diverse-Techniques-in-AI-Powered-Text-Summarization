# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm:
## Output:
## Zero-shot Prompts:
## Definition:
**Zero‑shot prompting** is a technique where a Large Language Model (LLM) is given a task instruction **without any prior examples** of how to complete that task. The model relies entirely on its pre‑trained knowledge and general language understanding to generate a response.
## Prompt:To generate an article on "The Basics of Blockchain Technology" in 500 words and provide an information about the sources.
## ChatGpt:

## Source Article

**The Basics of Blockchain Technology**

Blockchain technology is a decentralized digital system used to record and store data in a secure, transparent, and tamper-resistant manner. Originally developed as the underlying technology for cryptocurrencies like Bitcoin, blockchain has evolved into a powerful tool with applications across multiple industries such as finance, healthcare, supply chain management, and governance.

At its core, a blockchain is a distributed ledger. Instead of storing data in a single central location, it is shared across a network of computers, known as nodes. Each node maintains a copy of the entire blockchain, ensuring that the system is highly resilient to failures and cyberattacks. This decentralized nature eliminates the need for intermediaries such as banks or third-party organizations, making transactions faster and often more cost-effective.

A blockchain is made up of a series of blocks, where each block contains a list of transactions. Every block has three main components: data (transaction details), a unique identifier called a hash, and the hash of the previous block. These blocks are linked together in chronological order, forming a "chain." The use of cryptographic hashing ensures that once a block is added, it cannot be altered without changing all subsequent blocks, which requires consensus from the network. This makes blockchain highly secure and resistant to tampering.

One of the key features of blockchain technology is consensus mechanisms. These are protocols that ensure all nodes in the network agree on the validity of transactions before they are added to the blockchain. Common consensus methods include Proof of Work (PoW), where computational power is used to validate transactions, and Proof of Stake (PoS), where validators are chosen based on the amount of cryptocurrency they hold and are willing to "stake."

Another important concept is transparency. Since blockchain ledgers are often public, anyone can view the transactions recorded on them. This promotes trust among users and reduces the likelihood of fraud. However, while transactions are transparent, users' identities are typically protected through cryptographic techniques, ensuring privacy.

Blockchain technology also enables the use of smart contracts. These are self-executing contracts with predefined rules written in code. When certain conditions are met, the contract automatically executes the agreed-upon actions without requiring human intervention. Smart contracts are widely used in applications such as digital payments, insurance claims, and supply chain automation.

Despite its advantages, blockchain technology also faces challenges. Scalability is a major issue, as processing large volumes of transactions can be slow and resource-intensive. Additionally, energy consumption, especially in Proof of Work systems, has raised environmental concerns. Regulatory uncertainty and lack of standardization also pose barriers to widespread adoption.

In conclusion, blockchain technology represents a significant innovation in how data and transactions are managed. Its decentralized, secure, and transparent nature makes it a promising solution for many modern challenges. As the technology continues to evolve, it is expected to play a crucial role in shaping the future of digital systems.

**Sources of Information**

Nakamoto, S. (2008). Bitcoin: A Peer-to-Peer Electronic Cash System

Antonopoulos, A. M. (2017). Mastering Bitcoin (O'Reilly Media)

IBM Blockchain Resources – https://www.ibm.com/blockchain

Investopedia – Blockchain Basics Articles

World Economic Forum Reports on Blockchain Technology

Ethereum Whitepaper by Vitalik Buterin
## Result


