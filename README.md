# -Covid-19-Prediction-

## Prediction of COVID-19 based on Chest X-ray Images with CNN (Convolutional Neural Network)

This project involved building and training a Convolutional Neural Network (CNN) using Keras with TensorFlow as the backend. The goal was to predict whether patients were infected with COVID-19 or not based on their chest X-ray images. Data visualization was performed using Matplotlib, while data preprocessing and augmentation were done using TensorFlow 2.0.

The CNN model architecture consisted of sequential layers, including convolutional, pooling, dropout, and dense layers with ReLU activation. The output layer utilized sigmoid activation. The dataset comprised X-ray images of both non-COVID and COVID-infected patients, obtained from Kaggle. Evaluation metrics included training set, test set, and validation set accuracy. The Adam optimizer with a learning rate of 0.001 was chosen for gradient descent.

The project was conducted in the Google Colab environment.

Results of the model were following:

  1) Training Set Accuracy : 98.41 %
  2) Training Set Loss : 0.0490

  3) Validation Set Accuracy : 97.51 %
  4) Validation Set Loss: 0.0759

  5) Test Set Accuracy : 94.83 %
  6) Test Set Loss : 0.1141


##Dataset:

The dataset used in this project consists of lung X-ray images collected from both COVID-19 infected and non-infected patients. It provides a diverse range of images to train and evaluate our CNN model effectively. 


## Install Necessary Modules:


 -       pip install pandas
       
 -       pip install numpy  
  
 -       pip install tensorflow

Once Installed now we can import it inside our python code.


## Results:

Upon training the CNN model on the lung image dataset, we achieve exceptional accuracy in predicting COVID-19 infections based on uploaded lung X-ray images. Our system demonstrates great potential as an invaluable tool for healthcare professionals in diagnosing COVID-19 cases efficiently and accurately.


## Conclusion:

Our COVID-19 prediction system, utilizing lung image analysis and the power of CNNs, provides accurate predictions by simply uploading an image of the patient's lungs. This project contributes to the ongoing efforts in harnessing deep learning techniques to combat the pandemic. Further research and validation are recommended to deploy the system in real-world clinical settings, potentially assisting in early detection and patient management.
