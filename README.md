[![DOI](https://zenodo.org/badge/788787031.svg)](https://zenodo.org/doi/10.5281/zenodo.11070837)
# HCT-Unet
# Requirements
Pytorch 1.x
# Train/Test
* train
```
python train.py --dataset Synapse --max_epoch 400 --base_lr 0.05 --img_size 224 --batch_size 24
```
* test
```
python test.py --dataset Synapse --max_epoch 400 --base_lr 0.05 --img_size 224 --batch_size 24
```
