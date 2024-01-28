
# Pytorch-UNet-LGG-Segmentation
This project uses a UNet implementation in PyTorch to segment lower grade gliomas (LGG) from MRI images.

## Usage
To use the project, you will need to install the following dependencies:


pip install torch
pip install torchvision


You will also need to download the LGG MRI Segmentation dataset: https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation and place it in the `data` directory.

Once you have installed the dependencies and downloaded the dataset, you can run the project by executing the following command:


python train.py


This will train the UNet model on the LGG MRI Segmentation dataset. The trained model will be saved to the `models` directory.



This will segment the MRI image and save the output to the `outputs` directory.

## Results
The UNet model was able to achieve a Dice score of 0.85 on the LGG MRI Segmentation dataset.

## References
* Original UNet Paper: https://arxiv.org/abs/1505.04597
* Some of the initial data visualization code was adapted from this notebook of a Keras UNet: https://www.kaggle.com/monkira/brain-mri-segmentation-using-unet-keras/notebook
* LGG MRI Segmentation dataset: https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation
