<h1> Author Identification </h1>

<h2>Introduction</h2>
In this project assignment, a system was developed to analyze texts written by different authors and predict the author of an unknown text.
For this purpose, various feature extraction methods were applied, including TF-IDF-based word features.
Using these representations, classification was performed with various machine learning algorithms such as MLP(Multi Layer Perceptron).

<h2> Materials and Methods </h2>

<h3>Development Environment</h3>

This project aims to develop a text classification system capable of predicting the author of a given text based on samples from known authors. 
The project includes steps such as data analysis, feature extraction, model development, and evaluation of results. 
The development process was carried out in the Google Colab environment, a cloud-based Jupyter Notebook platform that enables interactive work in data science and machine learning projects.
The Python programming language was used throughout the project. For text representation, TF-IDF, was applied.
For classification, various models were trained and compared using algorithm such as MLP(Multi Layer Perceptron).

<h3> Dataset </h3>
The dataset used in the scope of the project was accessed through the integration of Google Drive with the Google Colab environment. 
The dataset consists of x authors, each having a varying number of texts.
These texts were analyzed in a way that reflects the linguistic characteristics of the authors and were used to train and test machine learning algorithms.


<h2>Evaluation Metrics</h2>

Various metrics are used to evaluate the performance of machine learning models.
These metrics measure whether the model makes correct classifications, as well as assess classification errors and the ratio of accurate predictions. 
In text classification tasks such as authorship attribution, these metrics are important for assessing the accuracy and reliability of the models.
Especially when it comes to distinguishing subtle differences between authors, the ability of algorithms to generalize correctly becomes a critical factor.
Therefore, evaluation using appropriate metrics is essential for measuring model success and identifying areas for improvement.

<h3>Accuracy</h3>
It represents the ratio of all correct predictions to the total number of predictions made by the model. Considering all classes, it indicates the proportion of correctly classified instances.
<h3>Precision</h3>
It indicates the ratio of true positive predictions to the total number of positive predictions made by the model. In other words, it measures how many of the instances predicted as positive by the model are actually positive.
<h3>Recall</h3>
It represents the ratio of true positive predictions to the total number of actual positive instances. This metric shows how well the model identifies the positive class.
<h3>F1 Score</h3>
It is the harmonic mean of precision and recall and is a more meaningful performance metric, especially in imbalanced datasets. It evaluates the overall model performance by considering both false positive and false negative predictions.


<h2>Result</h2>

In this study, author classification was performed using various text representation techniques and machine learning algorithms.
The models were evaluated using an 80% training and 20% testing split, and their performance was assessed based on Accuracy, Precision, Recall, and F1-Score metrics.

![image](https://github.com/user-attachments/assets/0871f3d1-2c97-4ca7-bdb7-9c56fe4b877f)



