# Zeroth-Order Submodular Maximization

This repository contains the code for the paper "Black box submodular maximization: Discrete and continuous settings" presented at the International Conference on Artificial Intelligence and Statistics (AISTATS) 2020.

## Abstract

Submodular maximization is a central problem in machine learning, but in many applications, we may not have access to the submodular function itself, but only to a stochastic noisy estimate of it. In this work, we study this problem of black-box submodular maximization in both discrete and continuous domains. We are the first to consider this problem in the continuous domain and show that by using a stochastic gradient estimator, we can achieve a (1/2-epsilon)-approximation for a monotone submodular function. We also show that a similar approach can be used in the discrete setting, and we provide a new algorithm that achieves a (1/2-epsilon)-approximation for a monotone submodular function.

## Citation

If you use this code in your research, please cite the following paper:

```
@inproceedings{chen2020black,
  title={Black box submodular maximization: Discrete and continuous settings},
  author={Chen, Lin and Zhang, Moran and Hassani, Hamed and Karbasi, Amin},
  booktitle={International Conference on Artificial Intelligence and Statistics},
  pages={1058--1070},
  year={2020},
  organization={PMLR}
}
```

## Usage

The code is provided in the `experiment/zeroth_order_experiment.ipynb` Jupyter notebook. You can run the notebook to reproduce the experiments from the paper.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
