# Kidney Exchange Model Comparison and Optimization

This project analyzes and compares multiple integer programming formulations for kidney exchange systems. The goal is to understand how different modeling approaches affect both the number of successful matches and computational performance as the size of the donor–recipient network increases.

## Overview
- Implemented and compared three optimization models for kidney exchange
- Evaluated match rates and runtime performance across datasets of varying sizes
- Analyzed trade-offs between computational efficiency and solution quality

## Models
- **Swap-based model (2-cycles only):** computationally efficient but limited in matching capability  
- **Edge-based model:** flexible formulation but computationally expensive at scale  
- **Cycle-based model (2- and 3-cycles):** achieves significantly higher match rates while remaining tractable  

## Key Findings
- Allowing 3-cycles substantially increases the number of successful matches  
- The edge-based formulation becomes impractical for large datasets due to runtime constraints  
- The cycle-based model provides the best balance between efficiency and match quality  
- Model choice becomes increasingly important as dataset size grows  

## Report
The full methodology, model formulations, and results are available here:

👉 **[Kidney_Exchange_Optimization_Report.pdf](./Kidney_Exchange_Optimization_Report.pdf)**

## Methods
- Integer programming
- Optimization modeling (AMPL)
- Computational analysis of runtime and scalability
