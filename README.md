# CausEB
Official implementation of the IJCV paper: "[A Causal Inspired Early-Branching Structure for Domain Generalization](https://arxiv.org/abs/2403.08649)".

Liang Chen, Yong Zhang, Yibing Song, Zhen Zhang, and Lingqiao Liu



## Preparation

### Dependencies

```sh
pip install -r requirements.txt
```

### Datasets

```sh
python -m domainbed.scripts.download --data_dir=/my/datasets/path
```

### Environments

Environment details used for the main experiments. Every main experiment is conducted on a single NVIDIA V100 GPU.

```
Environment:
	Python: 3.7.7
	PyTorch: 1.7.1
	Torchvision: 0.8.2
	CUDA: 10.1
	CUDNN: 7603
	NumPy: 1.21.4
	PIL: 7.2.0
```

## How to run, and collect results

Please refer to details in the original project page: [Domainbed](https://github.com/facebookresearch/DomainBed)



## Citation

```
@article{chen2024causal,
  title={A Causal Inspired Early-Branching Structure for Domain Generalization},
  author={Chen, Liang and Zhang, Yong and Song, Yibing and Zhang, Zhen and Liu, Lingqiao},
  journal={International Journal of Computer Vision},
  pages={1--21},
  year={2024},
  publisher={Springer}
}

```

Please contact me via email (liangchen527@gmail.com) if your have any questions regarding this project.
