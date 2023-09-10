# Quantifying Causes of Arctic Amplification via Deep Learning based Time-series Causal Inference

## Abstract
The warming of the Arctic, also known as Arctic amplification, is led by several atmospheric and oceanic drivers. However, the details of its underlying thermodynamic causes are still unknown. Inferring the causal effects of atmospheric processes on sea ice melt using fixed treatment effect strategies leads to unrealistic counterfactual estimations. Such methods are also prone to bias due to time-varying confoundedness. Further, the complex non-linearity in Earth science data makes it infeasible to perform causal inference using existing marginal structural techniques. In order to tackle these challenges, we propose TCINet - Time-series Causal Inference Network to infer causation under continuous treatment using recurrent neural networks and a novel probabilistic balancing technique. More specifically, we propose a neural network based potential outcome model using the long-short-term-memory (LSTM) layers for time-delayed factual and counterfactual predictions with a custom weighted loss. To tackle the confounding bias, we experiment with multiple balancing strategies, namely TCINet with the inverse probability weighting (IPTW), TCINet with stabilized weights using Gaussian Mixture Model (GMMs) and TCINet without any balancing technique. Through experiments on synthetic and observational data, we show how our research can substantially improve the ability to quantify leading causes of Arctic sea ice melt, further paving paths for causal inference in observational Earth science.
## Paper
The paper has been accepted in the proceedings of [ICMLA 2023](https://www.icmla-conference.org/icmla23/index.php). A copy of pre-print can be provided upon request.

## Code
In this repository, we have following folders:
1. Data 
2. Models 

## Citation
If you use this code for your research, please cite our paper.
