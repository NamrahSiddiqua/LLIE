# LLIE
## Low-light Image Enhancer from Paired Low-light Instances

### Introduction
In this project, we use Ubuntu 16.04.5, Python 3.7, Pytorch 1.12.0 and one NVIDIA RTX 2080Ti GPU.

### Datasets and results
Training dataset, testing dataset, and our predictions are available at https://drive.google.com/drive/folders/13aCSpL4x0_zYocxBEfOIYNYvnTg3ED0v?usp=sharing

### Testing
The pretrained model is in the ./weights.

Check the model and image pathes in eval.py, and then run:

python eval.py

### Training
To train the model, you need to prepare our training dataset.

Check the dataset path in main.py, and then run:

python main.py
