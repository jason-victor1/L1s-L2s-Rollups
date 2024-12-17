# Layer 1 and Layer 2 Blockchain Overview

This repository provides an overview of blockchain layers by focusing on Ethereum’s Layer 2 scaling solutions which are **Rollups**.

---

## **Table of Contents**
1. [Blockchain Layers](#blockchain-layers)
2. [What are Rollups?](#what-are-rollups)
3. [How Rollups Work](#how-rollups-work)
4. [Types of Rollups](#types-of-rollups)
   - Optimistic Rollups
   - Zero-Knowledge Rollups
5. [Blockchain Trilemma](#blockchain-trilemma)
6. [Conclusion](#conclusion)

---

## **Blockchain Layers**
### Layer 1 (L1)
- The **base layer** of the blockchain ecosystem.
- Handles consensus and transaction settlement.
- Examples: **Ethereum**, Bitcoin, Solana.
- Applications directly deployed here are called **dApps**.

### Layer 2 (L2)
- Built *on top of L1* to enhance scalability.
- Examples of L2 tools include:
   - **Chainlink**: Decentralized oracles.
   - **The Graph**: Event indexing.
- The most common L2 scaling solutions are **Rollups**.

---

## **What are Rollups?**
Rollups are **Layer 2 scaling solutions** that:
1. Reduce gas costs by bundling multiple transactions into one.
2. Increase Ethereum's transaction throughput.

---

## **How Rollups Work**
1. Users submit transactions to a **Rollup operator**.
2. The operator:
   - Bundles and compresses transactions **off-chain**.
   - Submits a single aggregated transaction back to **Layer 1**.
3. This reduces gas fees and scales the network efficiently.

---

## **Types of Rollups**
### Optimistic Rollups
- Assume all transactions are **valid by default**.
- Fraudulent transactions can be challenged using **fraud proofs** during a **challenge period**.

### Zero-Knowledge (ZK) Rollups
- Use **zk proofs** (validity proofs) to verify transactions.
- Key components:
   - **Prover**: Generates zk proofs.
   - **Verifier**: Validates the proofs.
   - **Witness**: Mathematical evidence used for verification.

---

## **Blockchain Trilemma**
A blockchain can achieve only **two out of three** properties:
1. **Decentralization**
2. **Security**
3. **Scalability**

Ethereum prioritizes **security** and **decentralization** at the cost of scalability. Rollups help solve this issue by enhancing **scalability** without compromising decentralization or security.

---

## **Conclusion**
Rollups enhance Ethereum’s scalability by:
- Processing transactions **off-chain**.
- Bundling transactions into a single and low-cost on-chain submission.
- Ensuring security and decentralization remain intact.

### **Technologies Involved**
- Ethereum L1
- Rollups (Optimistic, ZK)
- Chainlink and The Graph for decentralized data solutions.

