# CMIN-Dataset
This reposotory contains two new datasets for this ACL2023 main conference paper [Causality-Guided Multi-Memory Interaction Network for Multivariate Stock Price Movement Prediction](https://aclanthology.org/2023.acl-long.679/).

## Dataset Overview

As there are few existing high-quality datasets containing both texts and prices, we are making available two new benchmark datasets from 2018-01-01 to 2021-12-31:
- **CMIN-US** includes the top 110 stocks from US by market capitalisation;
- **CMIN-CN** consists of all 300 constituents of CSI300, a major Chinese stock market index;

Both datasets include comprehensive financial texts and stock price time series data, facilitating further research and benchmarking in the field. 
In our experiments, we have used news headlines instead of the entire texts for efficiency and noise reduction.

## Citation

If you use this dataset, please cite our paper:
```
@inproceedings{luo2023causality,
  title={Causality-Guided Multi-Memory Interaction Network for Multivariate Stock Price Movement Prediction},
  author={Luo, Di and Liao, Weiheng and Li, Shuqi and Cheng, Xin and Yan, Rui},
  booktitle={Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  pages={12164--12176},
  year={2023}
}
```