# private-credit-network
Network Model Simulating Risk in a Private Credit Market

# What Happens When a Lender Sneezes?

A contagion model exploring how defaults propagate through a private credit network.

## 🧩 Model Overview
Each lender and borrower is represented as a node. Edges represent exposures (loans).  
If a borrower defaults, lenders lose value proportional to exposure.  
If a lender’s equity is completely lost, it defaults - potentially triggering further losses.

## 🧠 Tools
- Python
- NetworkX
- Matplotlib
- Numpy

## 📊 Results
As network connectivity increases, the average number of defaults rises —  
highlighting the trade-off between diversification and systemic fragility.

## ▶️ Visualisation
Includes an animated ripple effect showing default propagation across the network.

## 📈 Next Steps
- Add collateral and liquidity layers
- Calibrate to real fund data

---
