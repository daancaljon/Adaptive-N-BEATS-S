# Adaptive-N-BEATS-S

This repo contains the code for the extensions to [N-BEATS-S](https://www.sciencedirect.com/science/article/pii/S016920702200098X) (Van Belle, J., Crevits, R., & Verbeke, W. (2022). Improving forecast stability
using deep learning. International Journal of Forecasting.) using adaptive loss balancing. It contains implementations for [GradNorm](http://proceedings.mlr.press/v80/chen18a.html?ref=https://githubhelp.com), (weighted) [Gradient Cosine Similarity](https://arxiv.org/abs/1812.02224), and [Random Weighting](https://arxiv.org/abs/2111.10603) (Cap). 

The following code was used as a starting point for the extensions to N-BEATS-S:
- N-BEATS-S developed by Jente Van Belle (https://github.com/KU-Leuven-LIRIS/n-beats-s)
- GradNorm algorithm by LucasBoTang (https://github.com/LucasBoTang/GradNorm)
- Gradient Cosine Similarity by Aviv Navon et al. (https://avivnavon.github.io/AuxiLearn/)


References: 
- Van Belle, J., Crevits, R., & Verbeke, W. (2022). Improving forecast stability using deep learning. International Journal of Forecasting.
- Lin, B., Feiyang, Y., Zhang, Y., & Tsang, I. (2022). Reasonable effectiveness of random weighting: A litmus test for multi-task learning. Transactions on Machine Learning Research.
- Du, Y., Czarnecki, W. M., Jayakumar, S. M., Farajtabar, M., Pascanu, R., & Lakshminarayanan, B. (2018). Adapting auxiliary losses using gradient similarity. arXiv preprint arXiv:1812.02224.
- Chen, Z., Badrinarayanan, V., Lee, C.-Y., & Rabinovich, A. (2018). Gradnorm: Gradient normalization for adaptive loss balancing in deep multitask networks.In International conference on machine learning, (pp. 794–803). PMLR.
