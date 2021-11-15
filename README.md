# Pneumonia-Classfication-PyTorch


* To Detect and Classify pneumonia using CNN. 
* I have used pytorch for classification.
* Images have been transformed, reshaped, rotated and normalized.
* Prepared train and test data.
* Took batch size of 64.
* Classifying images to one of the 2 categories: Normal and pneumona.
* Data augmentation to include more images.

## Languages Used 
**Python Version:** 3.9.0

## Resources and Tools Used
**Tools:** Jupyter Notebook

**Packages:** Pandas, NumPy, sklearn, cV2, glob and torch.

## Data Used
About the data: 
* The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

* Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

* For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

* **Data taken from kaggle**: https://www.kaggle.com/fahadmehfoooz/pneumonia-classification-using-pytorch/data

## Data Wrangling and Data Visualization
* Preparing the images by rescaling them.
* Visualizing the distribution of classes and the pictures of cells.
* Augmenting the data using an image data generator.
![alt text](https://github.com/fahadmehfooz/Brain-Tumor-Detection-Using-Keras-And-Pytorch-/blob/main/images/__results___62_0.png)

## Model Building 

First, I took a split on the data with training data as 80%. I tried to  model CNN with keras as well as pytorch.

* Used 3 convolutional layers.
* 1 max pool layerand 2 batchnorm layers.
* Compiled the model using Adam optimizer.
## Model performance

**Results:**

* CNN - Test accuracy: 76.76%
