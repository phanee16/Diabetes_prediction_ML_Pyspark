# Diabetes_prediction_ML_Pyspark

## Introduction

![image](https://user-images.githubusercontent.com/47351536/217939130-f04a9b65-9d65-4d8d-b33b-545df7375c1e.png)
Reference : Everyday health

### What is Diabetes? Why is it important to know about it?

Diabetes is a chronic health condition in which the body is unable to properly regulate blood sugar levels. There are two main types of diabetes: type 1 and type 2.

Type 1 diabetes is an autoimmune disorder in which the body's immune system attacks and destroys the cells that produce insulin, a hormone that regulates blood sugar levels. As a result, individuals with type 1 diabetes require regular insulin injections to regulate their blood sugar levels.

Type 2 diabetes, on the other hand, is characterized by insulin resistance, meaning that the body is unable to properly use the insulin it produces. This can lead to high blood sugar levels, which can cause a range of health problems if left untreated. Type 2 diabetes is often linked to obesity and a sedentary lifestyle.

The impact of diabetes on public health is significant. Diabetes is a leading cause of heart disease, stroke, kidney failure, blindness, and amputations. It also increases the risk of other health problems, such as neuropathy (nerve damage), periodontal disease (gum disease), and depression.

The increasing prevalence of diabetes, particularly type 2 diabetes, is a major public health concern. According to the World Health Organization (WHO), an estimated 422 million people worldwide had diabetes in 2014, and this number is expected to rise to over 629 million by 2045.

To address the impact of diabetes on public health, it is important to focus on prevention and early detection. This includes promoting healthy lifestyles, such as regular physical activity and a balanced diet, and screening for diabetes in at-risk populations. Effective treatment and management of diabetes can also help to reduce the risk of complications and improve overall health outcomes.

### Why are we using Pyspark for our project?

PySpark is a powerful tool for data processing and machine learning, and it can be used to classify diabetes in several ways. Here are some reasons why you might choose to use PySpark classification techniques for this task:

Scalability: PySpark is designed to handle big data, and it can easily scale to accommodate large datasets. This makes it well-suited for processing large healthcare datasets, which may include millions of patient records.

Speed: PySpark uses a distributed computing architecture, which means that processing is performed in parallel across multiple nodes. This allows for fast and efficient processing of large datasets.

Ease of use: PySpark provides a high-level API for machine learning, which makes it easier to develop and implement machine learning models. It also integrates with popular machine learning libraries, such as MLlib, which provides a range of algorithms for classification and other tasks.

Improved accuracy: PySpark can handle large, complex datasets and can consider multiple features or variables when making predictions. This can lead to improved accuracy compared to the traditional statistical methods or single-variable models.

Real-time predictions: PySpark can be used to make predictions in real-time, which can be useful for making early diagnoses and providing timely interventions in the case of diabetes.

In summary, PySpark provides a powerful and flexible platform for processing large healthcare datasets and developing machine learning models for classification, including the classification of diabetes. By leveraging the scalability, speed, and ease of use of PySpark, you can develop accurate and efficient models for predicting diabetes, which can help to improve public health outcomes.

## Literature Review:
There have been many studies that have used machine learning techniques to predict diabetes. These studies have used a range of algorithms and techniques, including decision trees, random forests, support vector machines, neural networks, and others. Here are some examples of previous studies and their results:

Decision Trees: A study published in the Journal of Medical Systems in 2011 used decision trees to predict diabetes. The study found that decision trees were effective in detecting risk factors for diabetes, such as age, BMI, and family history, and could accurately predict diabetes with a sensitivity of 83.3%.

Random Forests: Another study published in the Journal of Medical Systems in 2016 used random forests to predict diabetes. The study found that random forests were effective in identifying important risk factors, such as age, BMI, and blood pressure, and could predict diabetes with an accuracy of 75.4%.

Support Vector Machines: A study published in the Journal of Diabetes Research in 2016 used support vector machines (SVMs) to predict diabetes. The study found that SVMs were effective in identifying important risk factors, such as age, BMI, and blood pressure, and could predict diabetes with an accuracy of 77.6%.

Neural Networks: A study published in the Journal of Medical Systems in 2019 used neural networks to predict diabetes. The study found that neural networks were effective in detecting risk factors for diabetes, such as age, BMI, and family history, and could accurately predict diabetes with an accuracy of 85.7%.

Ensemble Methods: A study published in the Journal of Diabetes Research in 2020 used an ensemble of decision trees and random forests to predict diabetes. The study found that the ensemble method was effective in identifying important risk factors, such as age, BMI, and blood pressure, and could predict diabetes with an accuracy of 77.8%.

These studies demonstrate the effectiveness of various machine learning techniques for predicting diabetes, and show that a range of algorithms and techniques can be used for this task. However, the results of these studies may vary depending on the dataset used, the features selected, and other factors, and it is important to carefully evaluate the results of any study before applying the techniques in practice.
