---
title: "Bridging Normalization and Disentanglement in PG-GAN"
collection: publications
permalink: /publications/2020-10-16-causal-for-gan
date: 2020-10-16
authors: 'Xiao Liu*, Jiajie Zhang*, Siting Li*, Zuotong Wu, Yang Yu'
excerpt: 'arxiv 2020'
---
What mechanisms cause GAN's entanglement? Although developing disentangled GAN has attracted sufficient attention, it is unclear how entanglement is originated by GAN transformation. We in this research propose a difference-in-difference (DID) counterfactual framework to design experiments for analyzing the entanglement mechanism in on of the Progressive-growing GAN (PG-GAN). Our experiment clarify the mechanisms how pixel normalization causes PG-GAN entanglement during a input-unit-ablation transformation. We discover that pixel normalization causes object entanglement by in-painting the area occupied by ablated objects. We also discover the unit-object relation determines whether and how pixel normalization causes objects entanglement. Our DID framework theoretically guarantees that the mechanisms that we discover is solid, explainable and comprehensively.

Download paper [here](https://arxiv.org/pdf/2010.08402.pdf).

Recommended citation: 

```
@misc{liu2020differenceindifferences,
      title={Difference-in-Differences: Bridging Normalization and Disentanglement in PG-GAN}, 
      author={Xiao Liu and Jiajie Zhang and Siting Li and Zuotong Wu and Yang Yu},
      year={2020},
      eprint={2010.08402},
      archivePrefix={arXiv},
      primaryClass={id='cs.CV' full_name='Computer Vision and Pattern Recognition' is_active=True alt_name=None in_archive='cs' is_general=False description='Covers image processing, computer vision, pattern recognition, and scene understanding. Roughly includes material in ACM Subject Classes I.2.10, I.4, and I.5.'}
}
```

