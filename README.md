# Plant-disease-detection-system
Plant Leaf Disease Detection System utilizing AI algorithms

Steps to Implement the Plant Leaf Disease Prediction Project

    Mount the google drive on Google Collab Notebook and import the data set
    Import the required libraries
    Visualizing the images and Resize images
    Convert the images into a NumPy array and normalize them.
    Visualize the class count and Check for class imbalance
    Splitting the dataset into the train, validate, and test sets
    Performing one-hot encoding on the target variable
    Creating the model architecture, compiling the model, and then fitting it using the training data
    Plot the accuracy and loss against each epoch
    Make predictions on testing data
    Visualizing the original and predicted labels for the test images
    Deploy the project using Streamlit

Steps to Execute the Project
To generate Model

    Extract the contents of the zip folder.

    Create a Projects folder in your Google Drive. Within that create a folder named Plant-Leaf-Disease-Prediction

    Upload Plant_Leaf_Disease_Prediction.ipynb and Dataset folder into Plant-Leaf-Disease-Prediction on your Google account

    Open Plant_Leaf_Disease_Prediction.ipynb in Google Colab.

    Run Plant_Leaf_Disease_Prediction.ipynb  to generate the model. The Model plant_disease_model.h5 will be saved in Model Folder on your Google account.

To Run Streamlit Application.

    Download the plant_disease_model.h5 from your google account.

    Place the plant_disease_model.h5 and main_app.py into a folder in your machine.

    Install Anaconda Python Package

    Open the anaconda prompt in the current working directory.

    The following commands to generate the requirements.txt file

pip install pipreqs

pipreqs

Run the following command to install the required libraries.

pip install -r requirements.txt

Finally, run the following command to run the Streamlit application.

streamlit run main.py
