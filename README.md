# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Applications

## AIM
To evaluate and compare the effectiveness of prompting structures (Basic Prompt,Role Prompt,Context Prompt,Constraint Prompt,Output Format Prompt) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting structure provides the best summary in terms of:

1. Basic Prompt:
2. Role Prompt
3. Context Prompt
4. Constraint Prompt
5. Output Format Prompt

## Algorithm
## 1. Basic Prompt
Summarize the following 500-word article on "The Basics of Blockchain Technology"

**OUTPUT:**
Blockchain is a decentralized digital ledger that records transactions across many computers so that records cannot be altered retroactively. Each block contains transaction data, a timestamp, and a cryptographic hash of the previous block, forming a secure chain. Instead of relying on a central bank or authority, blockchain networks use consensus mechanisms like Proof of Work or Proof of Stake to verify transactions. While best known for powering cryptocurrencies such as Bitcoin, blockchain is also used in supply chain tracking, healthcare records, and smart contracts.

## 2. Role Prompt
Act as a Computer Science university professor who specializes in simplifying emerging technologies for undergraduate students. Summarize the following 500-word article on "The Basics of Blockchain Technology"

**OUTPUT:**
Think of a blockchain as a shared digital notebook copied across thousands of computers worldwide. Whenever a new group of transactions happens, it gets bundled into a "block," stamped with the time, and mathematically locked to the previous block using a digital fingerprint called a hash. Because every computer holds the same copy and must agree before adding new pages, no single person or company can secretly alter past entries. Originally built to run cryptocurrencies like Bitcoin without banks, this tamper-resistant design is now helping industries verify supply chains, secure medical data, and automate agreements through smart contracts.

## 3. Context Prompt
Act as a Computer Science university professor who specializes in simplifying emerging technologies. You are creating study notes for an educational platform used by first- and second-year undergraduate students who have no prior background in cryptography or distributed systems. Summarize the following 500-word article on "The Basics of Blockchain Technology" so they can quickly grasp why it matters and how it works

**OUTPUT:**
For students new to distributed systems, the easiest way to understand blockchain is to compare it to a traditional bank ledger. Normally, one central authority keeps the official record of who owns what. Blockchain removes that middleman by storing identical copies of the transaction ledger across a peer-to-peer network of computers. New transactions are grouped into blocks and linked together using cryptographic hashes—unique digital fingerprints that change if anyone tries to tamper with the data. Network participants verify new blocks through a shared agreement rule called consensus, making the system transparent, secure, and useful far beyond cryptocurrency in areas like supply chains and digital contracts.

## 4. Constraint Prompt
Act as a Computer Science university professor who specializes in simplifying emerging technologies. You are creating study notes for an educational platform used by first- and second-year undergraduate students with no prior background in cryptography or distributed systems. Summarize the following 500-word article on "The Basics of Blockchain Technology" under these rules:
Keep the total summary between 120 and 150 words.
Rely strictly on facts stated in the article without adding external concepts.Replace technical jargon with plain language, or define any essential term in parentheses.

**OUTPUT:**
Blockchain is a shared digital ledger maintained across a network of independent computers rather than controlled by a single central authority. Transactions are grouped into blocks, and each block is linked to the one before it using a hash (a unique digital fingerprint generated from the block's data). If anyone alters past data, the fingerprint changes and breaks the chain, alerting the network. Before a new block is added, participating computers must approve it through a consensus mechanism (an automated rule for network agreement). Originally created to support cryptocurrencies, blockchain now helps track goods in supply chains, protect records, and run self-executing agreements without intermediaries.

## 5. Output Format Prompt
Act as a Computer Science university professor who specializes in simplifying emerging technologies. You are creating study notes for an educational platform used by first- and second-year undergraduate students with no prior background in cryptography or distributed systems. Summarize the following 500-word article on "The Basics of Blockchain Technology" under these rules:
Keep the total summary between 120 and 150 words.
Rely strictly on facts stated in the article without adding external concepts.
Replace technical jargon with plain language, or define any essential term in parentheses.
Avoid introductory filler like "Here is a summary."
Format the response using this exact structure:
Core Idea: One-sentence takeaway (max 25 words).
Key Mechanisms: 3 bullet points explaining how the technology works.
Real-World Significance: 1 short sentence on why it is useful.
Key Terms: 2–3 essential terms from the text with one-line definitions.

**OUTPUT:**
**Core Idea:** Blockchain is a shared, tamper-resistant digital ledger that records transactions across a computer network without needing a central authority.
- **Key Mechanisms:**
  - Transactions are bundled into blocks and linked sequentially using cryptographic hashes (unique digital fingerprints).
  - Every computer in the peer-to-peer network holds an identical copy of the ledger, preventing single-point manipulation.
  - Network participants validate new blocks together using consensus rules before permanently adding them to the chain.
- **Real-World Significance:** Beyond powering cryptocurrencies, it enables transparent supply chain tracking, secure recordkeeping, and automated smart contracts without middlemen.
- **Key Terms:**
  - **Hash:** A unique digital fingerprint that links blocks together and exposes any tampering.
  - **Consensus Mechanism:** The shared verification rule computers follow to approve new transactions.
  - **Smart Contract:** A self-executing digital agreement stored on the blockchain that runs automatically when conditions are met.


## Result

The five progressive prompting techniques were successfully implemented and evaluated across multiple AI platforms for the 500-word Blockchain text summarization task, yielding the required comparative outcomes:

| Prompt Type | Accuracy | Coherence | Simplicity | Speed | User Experience |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **1. Basic** | High | Medium | Medium | Fast | Basic |
| **2. Role** | High | High | High | Fast | Good |
| **3. Context** | High | High | Very High | Fast | Good |
| **4. Constraint** | Very High | High | High | Medium | Very Good |
| **5. Output Format** | Very High | Very High | Very High | Medium | Excellent |

Thus, the experiment was successfully completed and the required results were obtained, demonstrating that progressively layering role, context, constraints, and an explicit output format produces the most accurate, coherent, and well-structured summary for undergraduate learners without compromising speed.

