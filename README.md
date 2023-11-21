# P-SCAN PULMONARY DISEASE DETECTOR

This system is a final year project developed by Isabela Forti at the Instituto Federal de São Paulo (IFSP), Brazil.
The main purpose of the project is to develop a CNN model which is able to analyze chest x-rays and classify them according to image patterns. The possible categories for classification are: Healthy, Bacterial Pneumonia, Viral Pneumonia or COVID-19.

- The model has an accuracy of approximately 87%

- An interface was created using Gradio. A web link is active for 72 hours as soon as the jupyter project is run. 

- The interface allows you to create a report based on the classification result. As soon as you click on "Create Report" button, a pdf is generated inside the directory "reports"

- To run the notebook you will need Jupyter Notebooks installed, as well as the requirements.txt. To install the requirements.txt run the following line: pip install -r requirements.txt

- The dataset can be found at: https://www.kaggle.com/datasets/artyomkolas/3-kinds-of-pneumonia. Please download it and extract it in the same folder where the notebook is located. Keep the name "Curated_X-Ray_Dataset" to avoid path errors.

- The majority of the code used as a reference for this project was extracted from: https://www.kaggle.com/code/faisalbinashraf/pneumonia-classification-using-cnn-visualization#Thank-you-for-your-time-and-curiosity-;)

- Thank you for your interest! :)
