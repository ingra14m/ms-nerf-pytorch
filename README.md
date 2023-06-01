# MS-NeRF-pytorch(CVPR 2023)

This repository contains the unofficial implementation of the following paper based on [nerf-pytorch](https://github.com/ingra14m/ms-nerf-pytorch):

> **Multi-Space Neural Radiance Fields**<br>
> Ze-Xin Yin, Jiaxiong Qiu, Ming-Ming Cheng, Bo Ren<sup>*</sup><br>
> IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**), 2023<br>

[[Arxiv](https://arxiv.org/abs/2305.04268)]
[[Project Page](https://zx-yin.github.io/msnerf/)] 
[[Dataset](https://drive.google.com/drive/folders/1gqmonTlR8LbJkljtT28S47N_o_YoExFz?usp=share_link)]

## Installation

```
git clone https://github.com/yenchenlin/nerf-pytorch.git
cd nerf-pytorch
pip install -r requirements.txt
```

## How To Run?

### Quick Start

To train synthetic_scenes:
```shell
python run_nerf.py --config configs/test.txt
```
- you can change the `datadir` in config file to train different dataset
- the interface is the same as [nerf-pytorch](https://github.com/yenchenlin/nerf-pytorch)


## Citation
```
@misc{mildenhall2020nerf,
    title={NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis},
    author={Ben Mildenhall and Pratul P. Srinivasan and Matthew Tancik and Jonathan T. Barron and Ravi Ramamoorthi and Ren Ng},
    year={2020},
    eprint={2003.08934},
    archivePrefix={arXiv},
    primaryClass={cs.CV}
}
```

```
@misc{lin2020nerfpytorch,
  title={NeRF-pytorch},
  author={Yen-Chen, Lin},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished={\url{https://github.com/yenchenlin/nerf-pytorch/}},
  year={2020}
}
```

```
@InProceedings{Yin_2023_CVPR,
    author    = {Yin, Ze-Xin and Qiu, Jiaxiong and Cheng, Ming-Ming and Ren, Bo},
    title     = {Multi-Space Neural Radiance Fields},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2023},
    pages     = {12407-12416}
}
```