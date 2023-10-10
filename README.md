# Identifying-Entities-in-Healthcare-Data

‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.

So, companies like ‘BeHealthy’ are providing medical services, prescriptions and online consultations and generating huge data day by day.

Suppose you have been given such a data set in which a lot of text is written related to the medical domain. As you can see in the dataset, there are a lot of diseases that can be mentioned in the entire dataset and their related treatments are also mentioned implicitly in the text, which you saw in the aforementioned example that the disease mentioned is cancer and its treatment can be identified as chemotherapy using the sentence.

But, note that it is not explicitly mentioned in the dataset about the diseases and their treatment, but somehow, you can build an algorithm to map the diseases and their respective treatment.

In this assignment,  performed the following broad steps:

1.Processed and modified the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
2.After that,defined the features to build the CRF model.
3.Then, applied these features in each sentence of the train and the test dataset to get the feature values.
4.Once the features are computed, defined the target variable and then build the CRF model.
5.Then, performed the evaluation using a test data set.
6.After that, created a dictionary in which diseases are keys and treatments are values.
