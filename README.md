# Name Entity Recognition in Healthcare Data
> Use CRF to build a model to identify entities(disease name and its probable treatment) from a data set in which a lot of text is written related to the medical domain. There are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text and list it out in the form of a table or a dictionary that can be used to 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- PROJECT BACKGROUND:  a CRF model to identify entities related to healthcare domain using libraries like spaCy, and sklearn_crfsuite. 
- BUSINESS PROBLEM: a hypothetical example of a health tech company called 'BeHealthy'. Suppose 'BeHealthy' aims to connect the medical communities with millions of patients across the country. 
'BeHealthy' has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.
So, companies like 'BeHealthy' are providing medical services, prescriptions and online consultations and generating huge data day by day.
Suppose you have been given such a data set in which a lot of text is written related to the medical domain. In the dataset, there are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text.
But, note that it is not explicitly mentioned in the dataset about the diseases and their treatment, but somehow, you can build an algorithm to map the diseases and their respective treatment.
You have been asked to determine the disease name and its probable treatment from the dataset and list it out in the form of a table or a dictionary.
- DATASET:
there are four datasets provided to you to process, which are as follows:
    - train_sent
    - test_sent
    - train_label
    - test_label
You have the train and the test datasets; the train dataset is used to train the CRF model, and the test dataset is used to evaluate the built model.
Each word in this dataset is provided in a single line. So, first, you need to club all these words together to form the sentences. Moreover, there are blank lines given in the dataset. These blank lines indicate that a new sentence is starting from the next line onwards to the next blank line.
In this 'train_sent' dataset, there are a total of 2,599 sentences when you form the sentences from the words. Similarly, there are a total of 1,056 sentences in the 'test_sent' dataset when you form the sentences from the words.

Now, in the datasets that are named 'train_label' and 'test_label' there are three labels that have been used in this dataset: O, D and T, which are corresponding to 'Other', 'Disease' and 'Treatment', respectively.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- spaCy
- sklearn_crfsuite

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

 

## Contact
Created by [@Biyani404198] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->