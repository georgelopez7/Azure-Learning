# Azure Learning

![Screenshot 2023-02-09 214526](https://user-images.githubusercontent.com/71076769/217946349-e50046ea-cc69-499f-97e2-93f36f9bc966.png)

---

### Table of Contents

- [Description](#description)
- [Azure Data Factory](#azure-data-factory)
- [Azure Machine Learning Studio](#azure-machine-learning-studio)

---

## Description

In this document, you will gain a comprehensive understanding of my experience with Microsoft Azure and its various services. Starting with data storage, Microsoft Azure provides two efficient solutions: Azure Blob Storage and Azure SQL Database. These services offer secure and scalable options for storing and managing data, and they can be seamlessly integrated into pipelines and machine learning models. 

To manage and automate data movement, Azure Data Factory was employed, while Azure Machine Learning Studio was utilized to construct and deploy machine learning models.

For more deatil into my experince with these tools please continue reading.


[Back To The Top](#azure-learning)

---

## Azure Data Factory

As part of my experience with Azure, Microsoft Azure Data Factory has proven to be a valuable tool in the management and analysis of data. As part of my training, I utilized Azure Data Factory to extract data from a source dataset and load it into a sink dataset (**from blob storage to a SQL database**) in preparation for machine learning models and exploratory analysis.

![Picture1](https://user-images.githubusercontent.com/71076769/217945697-6ae709c7-a7e4-4c73-852c-2f8ecc34f15e.png)

Additionally, within the Data Factory I created multiple sinks to provide more structure to the data in the inevitable SQL database. In order to achieve this structure I implemented data flows which allowed me to transform and clean the data before it is loaded into the sink datasets. The use of data flows and multiple sinks enabled me to create a schema for the data and organize it within an SQL database. This has been crucial in ensuring the data is structured and ready for analysis.

Finally, in order to reduce the time and effort of manaual data transfers I employed triggers to orchestrate the pipelines automatically, making the data pipeline process much more efficient.  

In conclusion, my experience using Microsoft Azure Data Factory has been highly effective in managing and analysing data. I have utilized its ability to extract and transfer data, create multiple sinks, implement data flows, and orchestrate pipelines automatically to provide data with an inherent well-structured schema available for future analysis. 

[Back To The Top](#azure-learning)

---

## Azure Machine Learning Studio

My experience with Azure Machine Learning Studio was focused on analyzing data related to brain strokes. The  data can be found in this repository under **brain_stroke.csv**.  

The first step was to select the specific columns required for the machine learning model. The *"id"* column was not selected as this could disrupt the training of the model. Additionally, an SQL transformation was implemented to remove any **"Unknown"** values in the *"smoking_status"* as this could cause bias in the model.

Next, I trained the model using Azure Machine Learning Studio. In the diagram Two-Class Logistic Regression was used to train the datset. The drag and drop functionality of this service made the process of creating this model simple and streamline.

<img width="293" alt="Screenshot_2023-02-09_214910" src="https://user-images.githubusercontent.com/71076769/217947221-ea5bc77a-9d75-403d-92c1-5e6376deb5f8.png">

Finally, I evaluated the results of the model, which gave me a clear understanding of its performance and accuracy.

![Accuracy_scores](https://user-images.githubusercontent.com/71076769/217941369-7839e0ab-878a-4384-ab21-70a4f07aad9e.png)

Below you can see the confusion matrix produced by the model.  

![confusion_matrix](https://user-images.githubusercontent.com/71076769/217941382-3f2680cb-b538-4211-acef-c4d782500c17.png)

Below you can see the importance of each feature in the model.

![feature_importance](https://user-images.githubusercontent.com/71076769/217941396-47d0ad80-3871-45e9-ae68-15edf7338081.png)

To conclude, my experience with Azure Machine Learning Studio has enabled the creation of a Two-Class Logistic Regression model to predict whether an individual is likely to have a brain stroke. The drag and drop functionality allowed for an efficient process of training and deploying the model and establishing its accuracy for future datasets.

[Back To The Top](#azure-learning)

---

## Author Info

LinkedIn - [George Lopez](https://www.linkedin.com/in/george-benjamin-lopez/)
