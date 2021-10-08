# Learning Inner-group Relations on Point Clouds 
# (ICCV 2021)

### [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Ran_Learning_Inner-Group_Relations_on_Point_Clouds_ICCV_2021_paper.pdf) | [ArXiv](https://arxiv.org/abs/2108.12468)

[Haoxi Ran](https://hancyran.github.io/), [Wei Zhuo](https://scholar.google.com.au/citations?user=Q-UjnzEAAAAJ&hl=en), Jun Liu, Li Lu

## Abstract
>The prevalence of relation networks in computer vision is in stark contrast to underexplored point-based methods. In this paper, we explore the possibilities of local relation operators and survey their feasibility. We propose a scalable and efficient module, called group relation aggregator. The module computes a feature of a group based on the aggregation of the features of the inner-group points weighted by geometric relations and semantic relations. We adopt this module to design our RPNet. We further verify the expandability of RPNet, in terms of both depth and width, on the tasks of classification and segmentation. Surprisingly, empirical results show that wider RPNet fits for classification, while deeper RPNet works better on segmentation. RPNet achieves state-of-the-art for classification and segmentation on challenging benchmarks. We also compare our local aggregator with PointNet++, with around 30% parameters and 50% computation saving. Finally, we conduct experiments to reveal the robustness of RPNet with regard to rigid transformation and noises.

## BibTex

If you like our work and think it helpful to your project, please cite it as follows.

```bibtex
@misc{ran2021learning,
      title={Learning Inner-Group Relations on Point Clouds}, 
      author={Haoxi Ran and Wei Zhuo and Jun Liu and Li Lu},
      year={2021},
      eprint={2108.12468},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
``` 
