# Brand Classification

A report on the project can be found [here](https://drive.google.com/file/d/1RWFEBZJ11qcmIWDgG-DstoZjAJt5KpDz/view?usp=sharing).

This project demonstrates the transfer of knowledge from three CNN networks (namely, *VGG-19*, *DenseNet-161*, and *ResNet-152*) pretrained on the ImageNet dataset onto a novel target dataset by finetuning the layers of the networks during the training phase. An ensemble model that combines the networks trained via transfer learning is also proposed to further increase the classification accuracy of the base models.

### Prerequisite
- python-3.6+
- pytorch-1.5.0+
- torchvision-0.60+
- numpy.-1.18.1+
---

### Dataset

The novel dataset (CL-20) is made up of eleven categories of clothing labels from popular fashion brands. Each category has a total of 200 images, except for one category which has 500 images. Sample images from each category are shown in the image below. 

<p align="center">
  <img src="https://github.com/estifanosORP/BrandClassification/blob/master/Dataset_rs.jpg" />
</p>

___

### Description of Folders

1. **Base_Models**: contains notebooks that were used to train and test the base models. 
2. **Comparion_Metrics**: contains notebooks that were written to compare corresponding networks pretrained on the ImageNet dataset with networks finetuned on the target dataset.
3. **EnsembleModel**: contains a notebook that combines the basemodels to form an ensemble model. 
4. **Label_Data_TrainTest**: contains the training and testing datasets. The directory tree looks as follows:

<p align="center">
  <img src="https://github.com/estifanosORP/BrandClassification/blob/master/directory%20tree_rs.jpg" />
</p>
