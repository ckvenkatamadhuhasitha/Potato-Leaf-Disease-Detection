🥔 Potato Leaf Disease Classification using CNN (TensorFlow)
This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify potato leaf images into various disease categories.

📁 Dataset
The dataset is loaded from the PlantVillage dataset, stored in Google Drive, and contains images of potato leaves classified into multiple categories. The data is split as follows:

80% for training

10% for validation

10% for testing

Images are resized to 256x256, and the dataset is batched using tf.keras.preprocessing.image_dataset_from_directory.

🛠️ Model Architecture
The model is a custom Convolutional Neural Network (CNN) built using:

Convolutional layers

MaxPooling layers

Dense (fully connected) layers

ReLU activation and softmax for output classification

The network is trained for 50 epochs with a batch size of 32 and 3 image channels (RGB).

🧪 Technologies Used
TensorFlow / Keras for model development

Google Colab for training using GPU acceleration

Matplotlib for training visualization and performance plots

🚀 How to Run
Upload the dataset to your Google Drive under Colab Notebooks/potato/PlantVillage

Mount Google Drive in the notebook

Run all cells to train and evaluate the model

📈 Results
Training and validation accuracies, along with the loss curves, are visualized using Matplotlib. The model demonstrates strong performance in classifying potato leaf diseases.
