# Towards urban flood susceptibility mapping using data-driven models in Berlin, Germany
 
## Input data:
A sample for flooded and non flooded locations and the used predictive features in the paper are available on: https://zenodo.org/record/7472764#.Y6RHuxWZO70


## Description:
We compared convolutional neural networks (CNNs) (image-based model) with traditional machine learning algorithms such as random forest (RF), support vector machine (SVM) and artificial neural networks (ANNs) to map urban flood susceptibility in Berlin, Germany. We used a flood inventory and eleven predictive features representing topographu, infrastructure and precipitation to develop the models. The results showed that the RF models outperformed other models and all the models performed well outside the training domain.

## Methodology
The main aim is to evalaute the models transferability to regions that were not included in the training data. We selected a study area in Berlin used the flood inventroy within this area to develop the models.  We divided the dataset into training (60 %), validation (20 %) and testing (20 %) datasets. Firstly, we used the trainng and validation dataset to train the model and tune the hyperparameters. Then, we used the testing dataset to evalaute the model performance among the training domain. Finally we used the reported flooded locations outside the training domain to evalaute the models'transferability in space.

![Figure S3 supporting information](https://user-images.githubusercontent.com/57235564/209140361-8ba5f05a-9862-4e0c-a590-2cc4edef5322.png)


## Models
We compared convolutional neural networks (CNNs) (image-based model) with traditional machine learning algorithms such as random forest (RF), support vector machine (SVM) and artificial neural networks (ANNs) to map urban flood susceptibility in Berlin, Germany. We used the LeNet 5 architecture for the CNN 

![Figure 4](https://user-images.githubusercontent.com/57235564/209140709-1e221507-bf10-49fe-85ca-5ac47f224116.png)


## Results
The models performed well among and outside the training domain. 

![Berlin_map](https://user-images.githubusercontent.com/57235564/209140115-4f79bece-d516-4496-b0d5-f3800c9a7041.jpg)
