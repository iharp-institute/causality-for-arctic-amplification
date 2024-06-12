# Estimating Direct and Indirect Causal Effects of Spatiotemporal Interventions in Presence of Spatial Interference

## Abstract
Spatial interference (SI) occurs when the treatment at one location affects the outcomes at other locations. Accounting for spatial interference in spatiotemporal settings poses further challenges as interference violates the stable unit treatment value assumption, making it infeasible for standard causal inference methods to quantify the effects of time-varying treatment at spatially varying outcomes. In this paper, we first formalize the concept of spatial interference in case of time-varying treatment assignments by extending the potential outcome framework under the assumption of no unmeasured confounding. We then propose our deep learning based potential outcome model for spatiotemporal causal inference. We utilize latent factor modeling to reduce the bias due to time-varying confounding while leveraging the power of U-Net architecture to capture global and local spatial interference in data over time. Our causal estimators are an extension of average treatment effect (ATE) for estimating direct (DATE) and indirect effects (IATE) of spatial interference on treated and untreated data. Being the first of its kind deep learning based spatiotemporal causal inference technique, our approach shows advantages over several baseline methods based on the experiment results on two synthetic datasets, with and without spatial interference. Our results on real-world climate dataset also align with domain knowledge, further demonstrating the effectiveness of our proposed method.

## Code
In this repository, we have the following folders:
1. Data (code to generate synthetic data) 
2. Baselines (existing causal inference methods for time-series and spatial data)
3. Models (variants of our proposed STCINet)
