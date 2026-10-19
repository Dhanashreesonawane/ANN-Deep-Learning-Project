# 🌸 Iris Flower Classification Using Artificial Neural Network (ANN)

## 📌 Project Overview

This project implements an Artificial Neural Network (ANN) for classifying Iris flowers into three species using the Iris dataset. The model learns patterns from flower measurements and predicts the species based on the input features.

The project was developed and executed using Python in Google Colab to explore the fundamentals of deep learning, neural network training, and multiclass classification.

## 🎯 Objectives

- Understand the fundamentals of Artificial Neural Networks.
- Explore and preprocess the Iris dataset.
- Build and train an ANN for multiclass classification.
- Predict Iris flower species using their physical measurements.
- Evaluate the model using appropriate classification metrics.
- Understand how deep learning can be applied to real-world classification problems.

## 📊 Dataset

**Dataset:** Iris Flower Dataset

The Iris dataset contains 150 samples belonging to three flower species:

- Iris setosa
- Iris versicolor
- Iris virginica

### Input Features

The model uses four numerical features:

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal in cm |
| Sepal Width | Width of the sepal in cm |
| Petal Length | Length of the petal in cm |
| Petal Width | Width of the petal in cm |

**Target Variable:** Iris flower species (3 classes)

Each species contains 50 samples in the standard Iris dataset.

**Dataset source:** [UCI Machine Learning Repository – Iris Dataset](https://archive.ics.uci.edu/dataset/53/iris)

## 🛠️ Technologies Used

- **Python** – Programming language
- **Google Colab** – Cloud-based development environment
- **NumPy** – Numerical computations
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization, if used
- **Scikit-learn** – Dataset utilities, preprocessing, and evaluation, if used
- **TensorFlow / Keras** – ANN model development and training, if used

*The libraries listed above should match the actual implementation in the notebook.*

## ⚙️ Project Workflow

1. **Data Loading:** Load the Iris dataset into the Python environment.
2. **Exploratory Data Analysis:** Examine the dataset, features, and target classes.
3. **Data Preprocessing:** Prepare the input features and encode target labels as required.
4. **Dataset Splitting:** Divide the data into training and testing sets.
5. **ANN Architecture:** Define the neural network layers and activation functions.
6. **Model Training:** Train the ANN using the training data.
7. **Model Evaluation:** Evaluate the trained model on unseen test data.
8. **Prediction:** Predict the species of Iris flowers from their measurements.
9. **Result Analysis:** Review model performance and visualizations, where available.

## 🧠 Artificial Neural Network

An Artificial Neural Network is a computational model inspired by the interconnected neurons of the human brain.

In this project, the ANN learns relationships between four flower measurements and three possible Iris species.

The model typically consists of:

- **Input Layer:** Accepts the four flower measurements.
- **Hidden Layer(s):** Learns patterns and relationships in the input data.
- **Output Layer:** Produces predictions for the three Iris species.

The exact architecture, number of neurons, activation functions, and optimizer depend on the implementation in the notebook.

## 📈 Evaluation Metrics

The model can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Training and validation loss, if recorded

Refer to the notebook for the actual evaluation results.

## 🚀 How to Run the Project

1. Open the notebook file in this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the downloaded `.ipynb` notebook or open it from GitHub.
4. Install any missing dependencies, if necessary.
5. Execute the notebook cells in sequence.
6. Review the model training, predictions, and evaluation results.

The standard Iris dataset can be loaded using Scikit-learn or obtained from the dataset source linked above, depending on the notebook implementation.

## 📂 Project Structure

```text
ANN-Deep-Learning-Project/
├── ANN_Deep_Learning_Project.ipynb
└── README.md
```

*Replace the notebook filename above with the actual filename in your repository.*

## 🔍 Key Learnings

- Fundamentals of Artificial Neural Networks and deep learning.
- Data preprocessing for machine learning.
- Multiclass classification using neural networks.
- Model training, testing, and performance evaluation.
- Using Python and Google Colab for deep learning experiments.

## 🔮 Future Improvements

- Experiment with different ANN architectures and hyperparameters.
- Compare ANN performance with traditional machine learning classifiers.
- Add visualizations such as a confusion matrix and training curves.
- Develop a simple web application for interactive Iris flower classification.

## 👩‍💻 Author

**Dhanashree Sonawane**

- GitHub: [Dhanashreesonawane](https://github.com/Dhanashreesonawane)


