# Power Aware Container Placement in Cloud Computing with Affinity and Cubic Power Model

### What this project is about
Optimizing container placement in cloud data centers by balancing:
- Power efficiency (using a realistic cubic CPU power model)
- Application–machine affinity & anti-affinity constraints
- Multi-resource awareness (CPU, memory, I/O, network)

### Why it matters
Modern data centers spend ~60% of their operational cost on electricity. This project shows how smart scheduling can save power, improve performance, and make cloud computing more sustainable.

### Key Highlights
First approach to integrate power, affinity/anti-affinity, and multiple resources in one framework
Four-phase solution: preprocessing → greedy heuristics → combined optimization → Genetic Algorithm refinement
Achieved up to:
- 26% lower total system cost
- 37% higher affinity payoff ratio
- 4% better affinity satisfaction vs. state-of-the-art methods

### Tech & Tools
- Implementation in C++ & Python
- Evaluated on Google Cluster Dataset + synthetic workloads
- Compared against GCCS and HOP-CAPM

### Python Libraries Used
- Numpy
- Matplotlib
- Pandas
- Mosek
- Make sure to install the above libraries before running the code using following command:
```bash
pip install numpy matplotlib mosek pandas
```

### How to run an IPYNB file
- Inside Jupyter Notebook, you can run each cell of the IPYNB file by clicking on it and pressing `Shift + Enter` or by using the `Run` button in the toolbar.
- Alternatively, you can run the whole notebook in a single go by using the `Run All` option in the toolbar.

### Link to the preprint version 
https://arxiv.org/abs/2408.01176

### Link to the paper 
https://link.springer.com/article/10.1007/s00607-025-01566-0

### Please cite our work as :
Sarkar, S., Sharma, N., Mittal, A. et al. Power aware container placement in cloud computing with affinity and cubic power model. Computing 107, 221 (2025). https://doi.org/10.1007/s00607-025-01566-0
