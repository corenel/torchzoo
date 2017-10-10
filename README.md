# TorchZoo
*torchzoo* is a zoo of models and datasets for PyTorch. Most of them are used frequently in my research life but not provided by `torchvision`.

This repository consists of:

- [torchzoo.datasets](#datasets) : Data loaders for popular vision datasets.
- [torchzoo.models](#models) : Definitions for popular model architectures.

## Datasets

The following dataset loaders are available:

* [MNIST-M](#mnist-m)
* [USPS](#usps)

### MNIST-M

The MNIST-M dataset consists of MNIST digits blended with random color patches from the BSDS500 dataset. Its structure is the same as MNIST.

[**Download link**](https://drive.google.com/open?id=0B0AsKkiz_kZRZUxMNW5YTlkzOUk)

Please unzip and place `mnist_m_train.pt` and `mnist_m_test.pt` in `$DATA_ROOT/processed` folder.

### USPS

The dataset refers to numeric data obtained from the scanning of handwritten digits from envelopes by the U.S. Postal Service. The original scanned digits are binary and of different sizes and orientations; the images here have been deslanted and size normalized, resulting in 16 x 16 grayscale images (Le Cun et al., 1990).

There are 7291 training observations and 2007 test observations, distributed as follows:

|       | 0    | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | Total |
| ----- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ----- |
| Train | 1194 | 1005 | 731  | 658  | 652  | 556  | 664  | 645  | 542  | 644  | 7291  |
| Test  | 359  | 264  | 198  | 166  | 200  | 160  | 170  | 147  | 166  | 177  | 2007  |

**Download link**:
- [GitHub](https://raw.githubusercontent.com/mingyuliutw/CoGAN_PyTorch/master/data/uspssample/usps_28x28.pkl)
- [Google Drive](https://drive.google.com/open?id=0B0AsKkiz_kZRNy11MHE3Q01CdEk)

Please place `usps_28x28.pkl` in `$DATA_ROOT` folder.

## Models
(WIP)
