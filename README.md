# Text-Mining

## Introduction
Text mining on mental health is a rapidly growing field that leverages natural language processing, machine learning, and other computational techniques to analyse and extract meaningful insights from text data related to mental health. The insights obtained from text mining on mental health may help identify patterns and trends related to mental health issues and can aid in the development of personalized mental health treatments. It can also help in identifying and tracking emerging trends, such as changes in public perceptions and attitudes towards mental health issues. “The automatic detection of mental health conditions is one of the most important and complex health concerns in the real world. Mental health affects the behaviour, thinking, & mood of individuals interacting with the world around them. Further, mental health problems are becoming a leading disability, contributing largely to the universal burden of disease.”

Text mining is a technique used to analyse large amounts of unstructured data related to mental health, including social media posts, online forums, and patient records. The application of text mining in mental health analysis can help researchers identify patterns and trends in people's mental health experiences, such as symptoms, coping mechanisms, treatment options, and support networks. Utilising text mining we can conduct sentiment analysis to identify the emotional state of people regarding their mental health. It can also be used to perform topic modelling to identify common themes, network analysis to understand social interactions, and classification to categorize mental health-related text into different groups.

The data may come from a variety of sources, such as social media posts, online forums, electronic medical records, and scientific publications. This approach can help identify common themes, sentiment, and opinions in mental health discussions, and may have applications in improving mental health diagnosis, treatment, and public health policies. Another important application of text mining on mental health is in the development of mental health policies and programs. By analysing large amounts of text data, policymakers can gain insights into the needs of individuals and communities, as well as the challenges they face, and can then develop policies and programs that are better tailored to address these needs.The insights gained from text mining can help develop targeted interventions and improve mental health support and resources. By analysing mental health-related text data, researchers can better understand people's mental health experiences and develop personalized interventions that meet the unique needs of different individuals.

## Context and dataset description 
Word clouds are a popular way of visually representing the most frequently used words in each text. They are simple to generate and provide a rapid snapshot of the words used most frequently in the text. Although they are not the most advanced tool for analysing sentiment, they can be helpful in pictorially illustrating the emotional content of a text. However, word clouds have their limitations in that they do not provide an in-depth analysis of the text, and the sentiment scores given to each word may not always correctly reflect the context in which it was used. As a result, it is suggested that other sentiment analysis tools be used alongside word clouds for a more accurate analysis.

For the current project we are using Mental Health Corpus in order to extract the commonly used word from texts related to people with anxiety, depression, and other mental health issues. We have first columns with the text along with a column which acts as flag if the word containing in the text is poisonous or not.


##	Approach
To perform sentiment analysis using word clouds, we will use a multi-step approach:
- Collect/Extract the text data for analysis – we will use Mental Health Corpus.
- Pre-processing or cleaning the text data. 
    - By Lowercasing texts
    - By removing URL and special characters
    - By removing stop words and punctuation.
    - Stemming
    - Lemmatising
- Bifurcating the dataset into poisonous and non-poisonous text datasets.
- Analysing commonly used word using Frequency Distribution Plot
- Utilising wordcloud to get a pictorial representation.



