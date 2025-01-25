# 🎓 Online Learning Applications

Welcome to the repository for the **Online Learning Applications**, developed during the academic year 2024/2025. This project focuses on designing **online learning algorithms** to optimize a marketing campaign, including pricing strategies and bidding in auctions.

🧑‍🤝‍🧑Thanks to [Andrea Bertogalli](https://github.com/andberto), [Niccolò Balestrieri](https://github.com/NiccoloBalestrieri) and [Francesco Cavalieri](https://github.com/KavaTappi)
## 📝 Overview

The goal of this project is to design and implement online learning algorithms to address two key challenges in a marketing campaign:
1. **Pricing Problem**: Determine the optimal price for products to maximize profits.
2. **Bidding Problem**: Optimize bids in auctions for advertising slots.

The project was conducted in the following environments:
- **Stochastic Environment**
- **Adversarial Environment**
- **Non-Stationary Environment**

---

## 🛠️ Methodology

### 🌟 Stochastic Environment
- **Pricing**:
  - Used **GP-UCB** to optimize pricing over a continuous range.
- **Bidding**:
  - Implemented two strategies:
    - **Multiplicative Pacing Strategy**
    - **UCB-Like Approach**

### ⚔️ Adversarial Environment
- **Pricing**:
  - Applied **EXP3** and **Hedge** algorithms on a discretized price set to adapt to dynamic user behavior.
- **Bidding**:
  - Used **Hedge Multiplicative Pacing** to optimize bids under adversarial conditions.

### 🔄 Non-Stationary Environment
- **Pricing**:
  - Developed algorithms to address non-stationary demand curves, including:
    - **CUSUM-UCB**
    - **Sliding Window-UCB**
  - Extended the problem to include two-item pricing strategies.

---

## 📊 Results

### 🌟 Stochastic Environment
- **GP-UCB** successfully converged to optimal pricing with minimal regret.
- **Bidding algorithms** maintained high performance across multiple trials.

### ⚔️ Adversarial Environment
- **EXP3** and **Hedge** demonstrated competitive performance in price optimization.
- **Hedge Multiplicative Pacing** effectively managed bidding in changing environments.

### 🔄 Non-Stationary Environment
- **CUSUM-UCB** and **Sliding Window-UCB** adapted to abrupt changes in the environment.
- Extended strategies to handle two products, optimizing their pricing simultaneously.

---

## 🌟 Key Features
- Evaluation of **pricing and bidding strategies** across multiple environments.
- Implementation of advanced **online learning algorithms** such as **GP-UCB**, **EXP3**, **Hedge**, and **CUSUM**.
- Analysis of cumulative regret, profits, and algorithm performance through extensive experimentation.

---
This README file provides an overview of the Online Learning Applications project conducted in the homonym course, A.Y. 2023-2024, under the supervision of Prof. Castiglioni Matteo and Genalti Gianmarco. The project was carried out by Niccolò Balestrieri, Andrea Bertogalli, and Nicolò Tombini from Politecnico di Milano, Italy.

For more detailed information, please refer to the project documentation and source code provided in this repository.
