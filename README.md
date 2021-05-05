![Python](http://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=ffffff)
![Linux](http://img.shields.io/badge/-Linux-0078D6?style=for-the-badge&logo=linux&logoColor=ffffff)
# Data-Analytics-Project
## Credit Card Fraud Detection
## Combination of Unsupervised and Supervised Technique in Credit Card Fraud Detection
This is a mini project at NITK Surathkal.
## Dataset-
Dataset is collected from Kaggle named creditcard.csv. This is a credit card dataset made by European cardholders in September 2013. The dataset is
extremely unbalanced, the actual classes are only 0.172% of all transactions. It holds only numeric variables there is no object variable is there in the dataset. All the numeric variables are taken after PCA transformation.
link to dataset- https://www.kaggle.com/mlg-ulb/creditcardfraud

## Idea-
This project proposes the implementation of a hybrid approach that makes use of unsupervised outlier scores to extend the feature set of a fraud detection classifier.We used outlier scores from the unsupervised outlier detection models and added them as the new features and fed the data to the classifier.We compared various classifiers and classifier models with outlier scores as features.In the classifiers Random forest classifier and SVC performed well with respect to accuracy,recall and F1 score.So,we selected them as base model for the further comparison for outlier scores.So,after adding them ,we compared SVC+outlier score and RFC+outlier score, CBLOF(cluster-based local outlier factor) outlier score increased the accuracy of both the models i.e,SVC and RFC. While we couldn’t attain our aim of 100% efficiency in fraud discovery, we made end up building a method that can, with sufficient time and data, get very near to that aim. As with any such project, there is some scope for advancement here. The very characteristics of this project admit for various algorithms to be combined as modules and their effects can be merged to improve the correctness of the final result.

##### A simple flow of the project-
![Screenshot](/images/flow_new.png)
<br>
<br>
<br>
##### Results only with supervised algorithms-
![Screenshot](/images/class.jpeg)
<br>
<br>
<br>
##### Results with Sampling Algorithms (SMOTE)- 
![Screenshot](/images/class+smote.jpeg)
<br>
<br>
<br>
##### Results with combination of all (Unsupervised + SMOTE + Supervised)- 
![Screenshot](/images/class+smote+outlier.jpeg)



## How to setup the project
This project is built using Python3+ on jupyter-notebook. All the required libraries are listed in the first part of every code file.
Make sure to install all of them to run the project smoothly.

##### Clone the project
```sh
$ git clone https://github.com/Akbhobhiya/Data-Analytics-Project.git
$ cd Data-Analytics-Project
```

### Contributer
<ul>
  <li> <a href="https://github.com/Akbhobhiya">Ashok Bhobhiya</a> </li>
</ul>
<ul>
  <li>Wish to Contributing</li>
  <li>Please feel free to send a pull request or create an issue if you find any.</li>
</ul>
