---
title: "Training-Free Robust Multimodal Learning via Sample-Wise Jacobian Regularization"
collection: publications
permalink: /publications/2022-04-05-multi-modal-adversarial
date: 2022-04-05
authors: 'Zhengqi Gao, Sucheng Ren, Zihui Xue, Siting Li, Hang Zhao'
excerpt: 'arxiv 2022'
---
Multimodal fusion emerges as an appealing technique to improve model performances on many tasks. Nevertheless, the robustness of such fusion methods is rarely involved in the present literature. In this paper, we propose a training-free robust late-fusion method by exploiting conditional independence assumption and Jacobian regularization. Our key is to minimize the Frobenius norm of a Jacobian matrix, where the resulting optimization problem is relaxed to a tractable Sylvester equation. Furthermore, we provide a theoretical error bound of our method and some insights about the function of the extra modality. Several numerical experiments on AV-MNIST, RAVDESS, and VGGsound demonstrate the efficacy of our method under both adversarial attacks and random corruptions.

Download paper [here](https://arxiv.org/pdf/2204.02485.pdf).

Recommended citation: 

```
@misc{gao2022trainingfree,
      title={Training-Free Robust Multimodal Learning via Sample-Wise Jacobian Regularization}, 
      author={Zhengqi Gao and Sucheng Ren and Zihui Xue and Siting Li and Hang Zhao},
      year={2022},
      eprint={2204.02485},
      archivePrefix={arXiv},
      primaryClass={id='cs.CV' full_name='Computer Vision and Pattern Recognition' is_active=True alt_name=None in_archive='cs' is_general=False description='Covers image processing, computer vision, pattern recognition, and scene understanding. Roughly includes material in ACM Subject Classes I.2.10, I.4, and I.5.'}
}
```

