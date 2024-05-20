# Image Quality Assessment

## Introduction

This repository is a collection of image quality assessment (IQA) methods for the purpose of doing survey to figure out the best method availabel in the market under Samsung PRISM. The IQA methods are categorized into three types: Full-Reference (FR), No-Reference (NR), and Reduced-Reference (RR). The IQA methods are sorted by the publication year in descending order. The code and keywords are provided if available.

## Non-Reference IQA (NR-IQA)

| Paper Link                                                                                                                                | Method            | Type         | Published           | Code                                                                                                                            | Keywords                                                                 |
| ----------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | ------------ | ------------------- | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| [arXiv](https://arxiv.org/abs/2204.08958)                                                                                                 | MANIQA            | NR           | CVPRW2022           | [Official](https://github.com/IIGROUP/MANIQA)                                                                                   | Transformer, multi-dimension attention, dual branch                      |
| [arXiv](https://arxiv.org/abs/2108.06858)                                                                                                 | TReS              | NR           | WACV2022            | [Official](https://github.com/isalirezag/TReS)                                                                                  | Transformer, relative ranking, self-consistency                          |
| [pdf](https://www.bmvc2021-virtualconference.com/assets/papers/0868.pdf)                                                                  | KonIQ++           | NR           | BMVC2021            | [Official](https://github.com/SSL92/koniqplusplus)                                                                              | Multi-task with distortion prediction                                    |
| [arXiv](https://arxiv.org/abs/2108.05997)                                                                                                 | MUSIQ             | NR           | ICCV2021            | [Official](https://github.com/google-research/google-research/tree/master/musiq) / [Pytorch](https://github.com/anse3832/MUSIQ) | Multi-scale, transformer, Aspect Ratio Preserved (ARP) resizing          |
| [arXiv](https://arxiv.org/abs/2108.07948)                                                                                                 | CKDN              | NR           | ICCV2021            | [Official](https://github.com/researchmm/CKDN)                                                                                  | Degraded reference, Conditional knowledge distillation (related to HIQA) |
| [pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Su_Blindly_Assess_Image_Quality_in_the_Wild_Guided_by_a_CVPR_2020_paper.pdf) | HyperIQA          | NR           | CVPR2020            | [Official](https://github.com/SSL92/hyperIQA)                                                                                   | Content-aware hyper network                                              |
| [arXiv](https://arxiv.org/abs/2004.05508)                                                                                                 | Meta-IQA          | NR           | CVPR2020            | [Official](https://github.com/zhuhancheng/MetaIQA)                                                                              | Meta-learning                                                            |
| [arXiv](https://arxiv.org/abs/2003.08932)                                                                                                 | GIQA              | NR           | ECCV2020            | [Official](https://github.com/cientgu/GIQA)                                                                                     | Generated image                                                          |
| [arXiv](https://arxiv.org/abs/1809.07517)                                                                                                 | PI                | NR           | 2018 PIRM Challenge | [Project](https://github.com/roimehrez/PIRM2018)                                                                                | 1/2 \* (NIQE + (10 - NRQM)).                                             |
| [arXiv](https://arxiv.org/abs/1804.01681)                                                                                                 | HIQA              | NR           | CVPR2018            | [Project](https://kwanyeelin.github.io/projects/HIQA/HIQA.html)                                                                 | Hallucinated reference                                                   |
| [arXiv](https://arxiv.org/pdf/1805.08493v1.pdf)                                                                                           | BPSQM             | NR           | CVPR2018            | []()                                                                                                                            | Pixel-wise quality map                                                   |
| [arXiv](https://arxiv.org/abs/1707.08347)                                                                                                 | RankIQA           | NR           | ICCV2017            | [Github](https://github.com/xialeiliu/RankIQA)                                                                                  | Pretrain on synthetically ranked data                                    |
| [pdf](https://openaccess.thecvf.com/content_cvpr_2014/papers/Kang_Convolutional_Neural_Networks_2014_CVPR_paper.pdf)                      | CNNIQA            | NR           | CVPR2014            | [PyTorch](https://github.com/lidq92/CNNIQA)                                                                                     | First CNN-based NR-IQA                                                   |
| []()                                                                                                                                      |                   |              |                     | []()                                                                                                                            |
| [arXiv](https://arxiv.org/abs/2005.13983)                                                                                                 | UNIQUE            | NR           | TIP2021             | [Github](https://github.com/zwx8981/UNIQUE)                                                                                     | Combine synthetic and authentic image pairs                              |
| [arXiv](https://arxiv.org/pdf/1907.02665.pdf)                                                                                             | DBCNN             | NR           | TCSVT2020           | [Official](https://github.com/zwx8981/DBCNN-PyTorch)                                                                            | Two branches for synthetic and authentic distortions                     |
| [pdf](http://www.jdl.link/doc/2011/20191226_08489929.pdf)                                                                                 | SFA               | NR           | TMM2019             | [Official](https://github.com/lidq92/SFA)                                                                                       | Aggregate ResNet50 features of multiple cropped patches                  |
| [pdf](https://drive.google.com/file/d/1tMjcllKP8SzTn-dWVmogxaCLpzL1L7nO/view)/[arXiv](https://arxiv.org/abs/1708.08190)                   | PQR               | NR/Aesthetic | TIP2019             | [Official1](https://github.com/HuiZeng/Unified_IAA)/[Official2](https://github.com/HuiZeng/BIQA_Toolbox)                        | Unify different type of aesthetic labels                                 |
| [arXiv](https://arxiv.org/abs/1612.01697)                                                                                                 | WaDIQaM (deepIQA) | NR/FR        | TIP2018             | [PyTorch](https://github.com/lidq92/WaDIQaM)                                                                                    | Weighted average of patch qualities, shared FR/NR models                 |
| [pdf](https://ieeexplore.ieee.org/ielx7/83/8347140/08352823.pdf)                                                                          | NIMA              | NR           | TIP2018             | [PyTorch](https://github.com/kentsyx/Neural-IMage-Assessment)/[Tensorflow](https://github.com/idealo/image-quality-assessment)  | Squared EMD loss                                                         |
| [pdf](https://ece.uwaterloo.ca/~z70wang/publications/TIP_E2E_BIQA.pdf)                                                                    | MEON              | NR           | TIP2017             |                                                                                                                                 | Multi-task: distortion learning and quality prediction                   |
| [arXiv](https://arxiv.org/abs/1904.06505)                                                                                                 | dipIQ             | NR           | TIP2017             | [download](https://ece.uwaterloo.ca/~k29ma/codes/dipIQ.rar)                                                                     | Similar to RankIQA                                                       |
| []()                                                                                                                                      |                   |              |                     | []()                                                                                                                            |
| [arXiv](https://arxiv.org/abs/1612.05890)                                                                                                 | NRQM (Ma)         | NR           | CVIU2017            | [Project](https://sites.google.com/site/chaoma99/sr-metric)                                                                     | Traditional, Super resolution                                            |
| [arXiv](https://arxiv.org/abs/1609.04757)                                                                                                 | FRIQUEE           | NR           | JoV2017             | [Official](https://github.com/utlive/FRIQUEE)                                                                                   | Authentically Distorted, Bag of Features                                 |
| [IEEE](https://ieeexplore.ieee.org/document/7501619)                                                                                      | HOSA              | NR           | TIP2016             | [Matlab download](https://ieeexplore.ieee.org/document/7501619)                                                                 | Traditional                                                              |
| [pdf](https://live.ece.utexas.edu/publications/2015/zhang2015feature.pdf)                                                                 | ILNIQE            | NR           | TIP2015             | [Official](http://www4.comp.polyu.edu.hk/~cslzhang/IQA/ILNIQE/ILNIQE.htm)                                                       | Traditional                                                              |
| [pdf](https://live.ece.utexas.edu/publications/2012/TIP%20BRISQUE.pdf)                                                                    | BRISQUE           | NR           | TIP2012             | [Official](https://github.com/utlive/BRISQUE)                                                                                   | Traditional                                                              |
| [pdf](https://live.ece.utexas.edu/publications/2012/saad_2012_tip.pdf)                                                                    | BLIINDS-II        | NR           | TIP2012             | [Official](https://github.com/utlive/BLIINDS2)                                                                                  |
| [pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.359.7510&rep=rep1&type=pdf)                                               | CORNIA            | NR           | CVPR2012            | [Matlab download](https://github.com/HuiZeng/BIQA_Toolbox)                                                                      | Codebook Representation                                                  |
| [pdf](https://live.ece.utexas.edu/publications/2013/mittal2013.pdf)                                                                       | NIQE              | NR           | SPL2012             | [Official](https://github.com/utlive/niqe)                                                                                      | Traditional                                                              |
| [pdf](https://www.imaging.utk.edu/research/wcho/references/2011%20TIP%20BLINDS2.pdf)                                                      | DIIVINE           | NR           | TIP2011             | [Official](https://github.com/utlive/DIIVINE)                                                                                   |

## Evaluation Metrics

| Techniques | JPEG2000 | JPEG   | WN     | GBLUR  | FASTFADING | ALL    |
| ---------- | -------- | ------ | ------ | ------ | ---------- | ------ |
| BLIND-II   | 0.9506   | 0.9419 | 0.9783 | 0.9435 | 0.8622     | 0.9202 |
| BRISQUE    | 0.9139   | 0.9647 | 0.9786 | 0.9577 | 0.8768     | 0.9395 |
| CKDN       | 0.8239   | 0.8288 | 0.6312 | 0.819  | 0.7251     | 0.8233 |
| CNNIQA     | 0.953    | 0.981  | 0.984  | 0.953  | 0.933      | 0.953  |
| DBCNN      | 0.94     | 0.953  | 0.948  | 0.947  | 0.94       | 0.87   |
| DipIQ      | 0.956    | 0.969  | 0.975  | 0.94   | 0.758      | 0.949  |
| FRIQUEE    | --       | --     | --     | --     | --         | --     |
| GIQA       | --       | --     | --     | --     | --         | --     |
| HIQA       | 0.983    | 0.961  | 0.984  | 0.983  | 0.989      | 0.982  |
| HOSA       | 0.8008   | 0.853  | 0.9416 | 0.9513 | 0.7688     | 0.5771 |
| HyperIQA   | --       | --     | --     | --     | --         | --     |
| ILNIQE     | 0.8939   | 0.9418 | 0.9807 | 0.9153 | 0.8327     | 0.903  |
| KonIQ++    | --       | --     | --     | --     | --         | --     |
| MANIQA     | --       | --     | --     | --     | --         | --     |
| MEON       | 0.925    | 0.979  | 0.958  | 0.946  |            | 0.944  |
| MetaIQA    | --       | --     | --     | --     | --         | --     |
| MUSIQ      | --       | --     | --     | --     | --         | --     |
| NIMA       | --       | --     | --     | --     | --         | --     |
| NIQE       | 0.9172   | 0.9382 | 0.9662 | 0.8594 | 0.9135     | 0.9135 |
| NRQM       | --       | --     | --     | --     | --         | --     |
| PI         | --       | --     | --     | --     | --         | --     |
| RankIQA    | --       | --     |        | --     | --         | --     |
| SFA        | --       | --     | --     | --     | --         | --     |
| TReS       | --       | --     | --     | --     | --         | --     |
| UNIQUE     | 0.94     | 0.953  | 0.948  | 0.947  | 0.94       | 0.87   |
| WaDIQaM    | --       | --     | --     | --     | --         | --     |
