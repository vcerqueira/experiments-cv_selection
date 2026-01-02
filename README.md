# Model Selection for Time Series Forecasting

This repository contains the supplementary material and experimental code for the paper:  
**"Model selection for time series forecasting: an empirical analysis of multiple estimators"**, published in *Neural Processing Letters* (2023).

---

## Citation

If you use this code or the findings in your research, please cite the following paper:

```bibtex
@article{cerqueira2023model,
  title={Model selection for time series forecasting: an empirical analysis of multiple estimators},
  author={Cerqueira, Vitor and Torgo, Luis and Soares, Carlos},
  journal={Neural processing letters},
  volume={55},
  number={7},
  pages={10073--10091},
  year={2023},
  publisher={Springer}
}
```


## Benchmarking Goals
The primary objective of this repository is to benchmark several time series cross-validation (CV) approaches for model selection. The analysis addresses two key questions:

1. Selection Accuracy: How often do specific cross-validation methods select the true "best" forecasting model?

2. Cost of Error (Regret): When a sub-optimal model is chosen, what is the performance difference (cost) between the selected model and the best possible one?

## Repository Structure

`scripts/get-estimations.r`: Script to execute the cross-validation procedures.

`scripts/analysis.r`: Scripts to calculate selection accuracy and the cost of errors.