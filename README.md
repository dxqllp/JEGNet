#  Joint Edge-aware and Global context for polyp segmentation with cross-layer mapping


##  Requirements

* torch
* torchvision 
* tqdm
* opencv
* scipy
* skimage
* PIL
* numpy
### 2.2. Framework Overview

<p align="center">
    <img src="imgs/framework-final-min.png"/> <br />
    <em> 
    Figure 1: Overview of the proposed JEGNet.
    </em>
</p>

####  1. Training

```bash
python train.py  --mode train  --dataset kvasir_SEG  
--train_data_dir /path  --valid_data_dir  /path
```

###  2. Inference

```bash
python test.py  --mode test  --load_ckpt checkpoint 
--dataset kvasir_SEG    --test_data_dir  /path
```