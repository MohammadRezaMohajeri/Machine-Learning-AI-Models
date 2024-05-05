Summary:
This repository includes an HTML file, ICB_Response_Prediction_DeepNeuralNetwork_Model.html, which details a deep neural network model used for immune checkpoint blockade (ICB) response prediction. Here's a brief overview:

  1. Model Overview:
    - The model uses a deep neural network to predict ICB therapy responses across PR (Partial Response), SD (Stable Disease), and PD (Progressive Disease).
     
    - The architecture comprises three dense hidden layers with ReLU activation and dropout regularization.

  
  3. Data Preparation:
    - Gene expression data is standardized, and class weights are computed to handle class imbalance.

  
  4. Model Training & Evaluation:
    - The model is trained with class weights, and its performance is assessed using ROC-AUC scores, confusion matrix, and classification report.

  
  5. Model Interpretation:
  SHAP (SHapley Additive exPlanations) is employed to interpret model predictions and identify critical features influencing the predictions.


Explore the HTML file to understand how the deep learning model is structured, trained, and evaluated, and gain insights into the gene expression features relevant to immune checkpoint blockade response.
