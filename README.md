# Shu's Data Science Project Portfolio


## Project 1: Predict atomic-scale glass fracture
- Investigated machine learning approaches to predict atomic-scale fracture behavior in silica glass
- Built a data pipeline in Python to serialize simulation data (in TB), and to extract features from serialized data. Then implemented feature selection using statistical testing (correlation plots, etc.)
- Through independent research, designed measures that describe glass crack and made visualizations to compare these measures (Image shows fracture atoms labeled in red)

![Fracture Descriptor](/images/84_layout.png)

- Explored different machine learning models, including SVM, Logistic with graph kernel and RNN (Image shows the prediction result from machine learning model)

![Model Predictions](/images/84_600.png)

## Project 2: Fast style transfer
- Developed a website where user can upload both a style and a content image.  And the web app trans-forms the style of the content image to that of the style image.
- Built a GANs model from scratch using VGG19 (an open-source pre-trained CNN).
- Deployed the model using Flask web framework (https://faststyle.herokuapp.com/)
