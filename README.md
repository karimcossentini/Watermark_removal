# watermark-no-watermark


## Name
Watermark/ No Watermark


## Project context

In this project, we use and compare multiple approaches to build a classification model that allows us to determine whether an image contains a watermark. Then we apply techniques that would allow us to remove the watermark from an image. 

Data Link: https://drive.google.com/file/d/17y1gkUhIV6rZJg1gMG-gzVMnH27fm4Ij/view?usp=sharing

## 1/ data_exploration.ipynb 
In this notebook, we investigate the kaggle dataset that we are using for this project https://www.kaggle.com/datasets/felicepollano/watermarked-not-watermarked-images. 


At first we load the data, showcase example instances then analyze the classes balance between the training and validation images.

## 2/ watermark_Logistic_regression_baseline.ipynb
In this notebook, we use a baseline logistic regression approach to classify watermarked images. After the classification, we evaluate the model's performance using the Accuracy metric.

## 3/ watermark_cnn_models.ipynb
In this notebook, we build a classification approach for watermarked/unwatermarked images while exploring various CNN architectures starting with a Basic convolutional neural network followed by state of the art deep learning models such as Resnet50 and EfficientNet.
We also provide evaluation for these different architectures.

## 4/ autoencoder_watermark.ipynb
In this notebook, we build a denoising autoencode and train it on 60000 samples to remove watermarks from watermarked images

## 4/ inpainting_autoencoder_evaluation.ipynb
in this notebook, we list the different evaluation techniques used to evaluate the performance of the implemented approaches.


