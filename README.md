# Classification model uses NVD to evaluate the severity of CVEs
# Introduction
This project utilizes the National Vulnerability Database (NVD) by the National Institute of Standards and Technology (NIST) to assess the severity level of Common Vulnerabilities and Exposures (CVEs). We leverage information from CVEs such as exploitability score, impact score, and vendor assessments to determine whether a CVE is severe or not.

# Purpose
This project is part of the training program for TeamQ, a small group within the Wanna.w1n club at the University of Information Technology - Vietnam National University, Ho Chi Minh City. The theme of this project is software security.

# Usage
1. Data Collection: You need to collect data from NVD, which can be done through the API or by downloading published data files. Then, process the CVE data as shown in ModuleA_DataFetch.ipynb to prepare it for the binary classification problem.

2. Model Building: Using information from the combined_data.csv, I have built a binary classification model to evaluate the severity based on base scores. Specifically, the model I used is a DNN model with ReLU and sigmoid activation functions, and binary_crossentropy loss function.

3. Evaluating CVEs: I employ common evaluation metrics for classification problems, including accuracy, precision, recall, and f1-score.

# Conclusion
This project harnesses information from the NVD dataset to construct a simple model for classifying the severity level of CVEs.
