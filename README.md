# Disaster-Responsiveness-based-on-Machine-Learning

An Effective Disaster Responsiveness based on Machine Learning Approach

"Ineffective disaster response can be tragic outcome for many".

- GOAL: To categorize messages collected from various disasters according to their content.

- DATASET: Kaggle: https://www.kaggle.com/datasets/landlord/multilingual-disaster-response-messages?select=disaster_response_messages_training.csv

30,000 messages --> thirty-six distinct label classes. 
Input data -->thousands of untranslated disaster-related messages and their English translations.
Annotated data -->forty class labels for intent and content. 
Binary --> 1= related, 0=not related.

![image](https://github.com/code-mj/isaster-Responsiveness-based-on-Machine-Learning/assets/25456564/1cc53277-b832-4e3b-b220-2e9603e32f5c)


- The python code is in jupyter notebook and the model is trained and tested for the dataset in csv file. The generated model is saved in cache folder. Necessary packages are mentioned as part of toolkits. All code is written in Python 3.

TOOLKITS:

Jupyter Notebook,
VS Code

Python Libraries:
Pandas,
NumPy,
Scikit-learn, 
NLTK,
re,
SQLalchemy & SQLite3,
Pickle

- Model was tried out using 5 classifiers: RandomForestClassifier, ExtraTreesClassifier, GradientBoostingClassifier, AdaBoostClassifier and Support Vector Classifier

- CONCLUSION:
Based on our experiment, we found that AdaBoostClassifier model outperforms the other models based on evaluation matrix report with precision “0.75”, recall “0.61” and F1 score “0.66”.
We were successfully able to categorize each text message into its appropriate categories such as "Flood", "Storm", "aid_related" etc. We have even tested the model by providing the dummy messages to the model and it was able to classify whether the messages were related to disastrous
events or not related.
