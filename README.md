## Car Damage Assessment
# Detecting whether a car is damged or not using transfer learning.
Dataset was sourced from https://docs.google.com/forms/d/e/1FAIpQLSfuMMGafmiZ35alIgYkZeyGkR6gHhBURjxJPSe6aB6CWjN1EA/viewform under under the Open Data Commons Attribution License: https://opendatacommons.org/licenses/by/1.0/
# Preprocessing
The 3 channel images were resized according to the requirment of the model. Data Augmentation was applied to reduce overfitting and increase total number of samples.
# Training
All the metrics and information related to how the model is trained, and the accuracy and loss metrics have been included in the notebook.
# Explanations
Saliency Maps have been used for the purpose of generating explanations as to why the model is classifying an image of a car is damaged. They are present in the notebook itself
