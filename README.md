# NeurIPS2022 "Understanding Non-linearity in Graph Neural Networks from the Bayesian-Inference Perspective"
By Rongzhe Wei, Haoteng Yin, Junteng Jia, Austin R. Benson, Pan Li

## Introduction
Graph neural networks (GNNs) have become the de-facto standard used in many graph learning tasks due to their super empirical performance. Researchers often attribute such success to non-linearity in GNNs which associates them with great expressive power. However, for node classification tasks, many studies have shown that non-linearity to control the exchange of features among neighbors seems not that crucial. In this work, we resort to understand the effect of non-linearity by comparing with the linear counterparts for node classification tasks from a Bayesian Inference perspective.

## Main Results
* When the node attributes are less informative compared to the structural information, non-linear
propagation and linear propagation have almost the same mis-classification error.
* When the node attributes are more informative, non-linear propagation shows advantages. The
mis-classification error of non-linear propagation can be significantly smaller than that of linear
propagation with sufficiently informative node attributes.
* When there is a distribution shift of the node attributes between the training and testing datasets,
non-linearity provides better transferability in the regime of informative node attributes.

## Run Real Dataset Examples
We provide examples with minimal code to run real dataset experiments in `./Neurips2022_Understanding_Non_linearity_in_Graph_Neural_Networks_from_the_Bayesian_Inference_Perspective_Experiments.ipynb`, which includes experiemnts on PubMed, Cora, Citeseer under both Gaussian and Laplacian assumptions.

**Colab:** <a href="https://colab.research.google.com/drive/1dkcA2HheSy7y5ivtv2Esc_pjbxwOOin5?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Colab"></a> to play with `Neurips2022_Understanding_Non_linearity_in_Graph_Neural_Networks_from_the_Bayesian_Inference_Perspective_Experiments.ipynb` in Colab.


## Reference

If you find our paper and repo useful, please cite our paper:
```bibtex
@article{wei2022understanding,
  title={Understanding Non-linearity in Graph Neural Networks from the Bayesian-Inference Perspective},
  author={Wei, Rongzhe and Yin, Haoteng and Jia, Junteng and Benson, Austin R and Li, Pan},
  journal={Advances in Neural Information Processing Systems},
  year={2022}
}
```
