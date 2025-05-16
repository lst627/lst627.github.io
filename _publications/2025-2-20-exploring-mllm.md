---
title: "Exploring How Generative MLLMs Perceive More Than CLIP with the Same Vision Encoder"
collection: publications
permalink: /publications/2025-2-20-exploring-mllm
date: 2025-2-20
authors: 'Siting Li, Pang Wei Koh, Simon Shaolei Du'
excerpt: 'ACL 2025 (main) 

          CVPR 2025 MAR Workshop'
---
Recent research has shown that CLIP models struggle with visual reasoning tasks that require grounding compositionality, understanding spatial relationships, or capturing fine-grained details. One natural hypothesis is that the CLIP vision encoder does not embed essential information for these tasks. However, we find that this is not always the case: The encoder gathers query-relevant visual information, while CLIP fails to extract it. In particular, we show that another branch of Vision-Language Models (VLMs), Generative Multimodal Large Language Models (MLLMs), achieve significantly higher accuracy than CLIP in many of these tasks using the same vision encoder and weights, indicating that these Generative MLLMs perceive more -- as they extract and utilize visual information more effectively. We conduct a series of controlled experiments and reveal that their success is attributed to multiple key design choices, including patch tokens, position embeddings, and prompt-based weighting. On the other hand, enhancing the training data alone or applying a stronger text encoder does not suffice to solve the task, and additional text tokens offer little benefit. Interestingly, we find that fine-grained visual reasoning is not exclusive to generative models trained by an autoregressive loss: When converted into CLIP-like encoders by contrastive finetuning, these MLLMs still outperform CLIP under the same cosine similarity-based evaluation protocol. Our study highlights the importance of VLM architectural choices and suggests directions for improving the performance of CLIP-like contrastive VLMs.

Download paper [here](https://arxiv.org/pdf/2411.05195v2).

Recommended citation: 

```
@article{li2024erroneous,
  title={On Erroneous Agreements of CLIP Image Embeddings},
  author={Li, Siting and Koh, Pang Wei and Du, Simon Shaolei},
  journal={arXiv preprint arXiv:2411.05195},
  year={2024}
}
```

