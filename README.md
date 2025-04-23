# SuiMarket Project Overview

## **1. Introduction**

SuiMarket is a decentralized prediction market platform built on the Sui blockchain. It allows users to trade shares representing the likelihood of real-world event outcomes. The platform operates using Sui-native infrastructure, leveraging Move smart contracts for trustless operations, DeepBook for on-chain order matching, and Walrus for decentralized frontend hosting. Transactions are conducted in USDC, requiring only a compatible crypto wallet with no KYC.

## **2. Product Structure**

### **2.1 Functional Features**

#### **Markets**
- **Event Description and Outcomes**: Clear, verifiable event descriptions with defined outcomes (e.g., Yes/No or multiple options).
- **Market Resolution**: Outcomes verified using UMA’s Optimistic Oracle with a dispute resolution mechanism.
- **Liquidity and Incentives**: Rebates for early liquidity providers and share rewards (Phase 2).

#### **User Interaction**
- **Wallet Integration**: Sui-compatible wallets supporting USDC.
- **Trading**: Buy, sell, or trade outcome shares in USDC.
- **Settlement**: Automated payouts via smart contracts.

#### **Order Book System**
- **Order Matching**: On-chain Central Limit Order Book (CLOB) powered by DeepBook.

#### **Revenue Model**
- Transaction fees ranging from 0.1% to 2%.

### **2.2 Admin Features**
- Market creation and category management.
- Market suspension and refunding (Phase 2).

### **2.3 Reporting (Phase 2)**
- Reports on collateralization, liquidity, and suspended markets.

## **3. Technical Architecture**

### **3.1 Blockchain Integration**
- **Smart Contracts**: Built using Sui Move for automation and upgradeability.
- **Oracles**: UMA’s Optimistic Oracle for outcome verification.
- **Order Book**: DeepBook for on-chain order matching.

### **3.2 Infrastructure**
- **Frontend Hosting**: Decentralized hosting via Walrus.
- **Development Tools**: AI-assisted tools for secure and efficient development.

### **3.3 User Requirements**
- Wallet compatibility with no KYC requirements.

## **4. Gnosis Conditional Tokens Framework**

- **Market Creation**: Conditional tokens issued for each outcome.
- **Trading**: Prices reflect probabilities (e.g., $0.20 = 20% likelihood).
- **Resolution**: Winning tokens pay $1; losing tokens are worthless.

## **5. Roadmap**

### **Phase 1: MVP**
- Binary markets, basic trading, and resolution features.

### **Phase 2: Advanced Features**
- Multi-outcome markets, advanced order types, and reporting tools.

