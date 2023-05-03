# Diff-SCM 

Code for the paper [Diffusion Causal Models for Counterfactual Estimation](https://arxiv.org/abs/2202.10166).

![Image](assets/diffusion_causal_relationships.png)


## Paper Abstract

We consider the task of counterfactual estimation from observational imaging data given a known causal structure. In particular, quantifying the causal effect of interventions for high-dimensional data with neural networks remains an open challenge. Herein we propose Diff-SCM, a deep structural causal model that builds on recent advances of generative energy-based models. In our setting, inference is performed by iteratively sampling gradients of the marginal and conditional distributions entailed by the causal model. Counterfactual estimation is achieved by firstly inferring latent variables with deterministic forward diffusion, then intervening on a reverse diffusion process using the gradients of an anti-causal predictor w.r.t the input. Furthermore, we propose a metric for evaluating the generated counterfactuals. We find that Diff-SCM produces more realistic and minimal counterfactuals than baselines on MNIST data and can also be applied to ImageNet data.

