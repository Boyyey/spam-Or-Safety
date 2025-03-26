#📱 SMS Spam Classifier 🤖
This project implements a machine learning model to classify SMS messages as "Spam" or "Ham" (Not Spam). It uses a neural network trained on the SMSSpamCollection dataset and provides a simple GUI for predicting the class of a message.

#🛠️ Features
SMS Classification: Detect spam messages in real-time.

Neural Network Model: Built using TensorFlow/Keras.

Vectorization: Text messages are converted into numeric features using TfidfVectorizer.

GUI: User-friendly interface built with Tkinter to interact with the classifier.

Model: The model is saved and ready for future use.

#📂 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/sms-spam-classifier.git
cd sms-spam-classifier
Install dependencies: Ensure you have Python installed, then install the required libraries:

bash
Copy
Edit
pip install -r requirements.txt

#📋 How to Use
Extract the dataset: The project uses a ZIP file containing the SMSSpamCollection. You'll need to download it and place it in the correct location.

Run the script:

bash
Copy
Edit
python sms_spam_classifier.py
Predict Messages:

Enter a message in the text box and click Predict.

The model will classify it as either "Spam" or "Ham".

#📊 Model Performance
The model is trained with the following:

Model: Simple feed-forward neural network

Loss Function: Binary Cross-Entropy

Optimizer: Adam

Evaluation: Accuracy on the test set

#⚙️ Dependencies
pandas

tensorflow

sklearn

tkinter

numpy

These are listed in the requirements.txt file.

#💾 Saving and Loading the Model
After training, the model is saved as sms_spam_classifier_model.h5.

You can reload the model later for predictions.

#📸 Screenshots

User interface to enter messages and predict spam classification.

#🧑‍💻 Contributing
If you want to improve the project, feel free to open an issue or submit a pull request. Contributions are welcome! 🎉
