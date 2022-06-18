# Class-Imbalance-Problem-using-Inverse-Random-UnderSampling-IRUS-


# Problem Statement
Many real world classification problems are represented by highly unbalanced data sets, in which, the number of samples from one class is much smaller than from another. This is known as class imbalance problem and is often reported as an obstacle to constructing a model that can successfully discriminate the minority samples from the majority samples. Generally, the problem of unbalanced data sets occurs when one class repre- sents a rare or positive concept while the other class represents the negative concept, so that the examples from the negative class outnumber the examples from the positive class. This type of data is found, for example, in the multi-label classification problem where only few samples belong to the positive class; in medical record databases for rare diseases where a small number of patients would have a particular disease.

# Solution
The main idea is to severely under sample the majority class multiple times with each subset having fewer examples than the minority class. For each training set we then find a decision boundary which separates the majority class from the minority class. As the number of positive samples in each training set is greater than the number of negative samples, the focus in machine learning is on the positive class and consequently it can invariably be successfully separated from the negative class training samples. Thus, each training set yields one classifier design. By combining the multiple designs through fusion, we construct a composite boundary between the majority class and the minority class.The proposed methodology is applied on "HABERMAN" ('https://raw.githubusercontent.com/jbrownlee/Datasets/master/haberman.csv') data set and experimental results indicate a significant increase in performance when compared with many existing class-imbalance learning methods.

# Research Paper
https://ieeexplore.ieee.org/document/8361344
