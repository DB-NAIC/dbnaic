# DBNAIC
This repository contains the reference code for the paper "Dual Branch Non-Autoregressive Image Captioning".

# Requirements
- Python 3.7
- Pytorch 1.12
- Torchvision 0.13
- timm 0.6.11
- numpy
- tqdm

# Data preparation
The necessary files in training and evaluation are saved in `mscoco` folder, which is organized as follows:
```python
mscoco/
|--feature/
  |--region/
  |--grid/
```
Download the image features from [GoogleDrive](https://drive.google.com/file/d/1muydp9MVCUY4-hoKTsJvk4dZoycnrzbj/view?usp=sharing) and put into `mscoco/feature/coco2014`.

# Training
```python
python train.sh
```

# Evaluation
You can download the pre-trained model from [GoogleDrive](https://drive.google.com/file/d/19y8ZcNIMdqrqaw5K6lOgb90wxxrY690b/view?usp=sharing) and put it into `experiments/EENAIC/snapshot/`.
```python
python eval.sh
```
| BLEU-1      | BLEU-4      | METEOR      | ROUGE-L     | CIDEr       |     
| ----------- | ----------- | ----------- | ----------- | ----------- |
| 81.7        | 39.5        | 28.8        | 59.4        | 128.8       |
