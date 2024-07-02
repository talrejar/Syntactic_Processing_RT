# Syntactic_Processing

# Introduction
A health tech company called ‘BeHealthy’. They aim to connect the medical communities with millions of patients across the country. BeHealthy has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.

# Problem Statement
BeHealthy require predictive model which can identify disease and treatment from the patients interaction with doctor or ordering medicines online

# Observation
Here, idea is to extract the useful information from text and in addition to that the entity of the useful information also need to be identified.
Because the information we are planning to extract from the statement/interactions between doctor and patients are related to medical terms which are not regular usage day-to-day words.

# Approach
By observing the requirement, it is clearly visible that we have to process the textual sentence and identify the entities like Disease and Treatment. We can predict these all requirements using - CRF (Conditional Random Field) classifier - Random Forest Classifier - HMM (Hidden Markov Model)

# Library Explanation
1. Pandas - Dataframe, Content storage and processing
2. Regular Expression (re) - Identify the textual pattern
3. SpaCy - NLP, POS tag check

Sklearn_CRFsuite - Model building and Evaluation
# Syntactic_Processing_RT
