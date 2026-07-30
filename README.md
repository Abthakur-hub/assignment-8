# 🧠 AI-ML Assignment 8

## Handwritten Digit Recognition using Artificial Neural Networks (ANN)

---

# 👨‍🎓 Student Information

| Field                   | Details                                      |
| ----------------------- | -------------------------------------------- |
| **Name**                | Abhishek Thakur                              |
| **Registration Number** | 23MIM10078                    |
| **Application Number**  | IN26011189                      |
| **Batch Number**        | YOUR_BATCH_NUMBER                            |
| **Course**              |  1A|
| **University**          | VIT Bhopal University                        |

---

# 📌 Objective

The objective of this assignment is to develop an Artificial Neural Network (ANN) for recognizing handwritten digits (0–9) using the MNIST Handwritten Digits Dataset. The project demonstrates the complete machine learning workflow, including data understanding, preprocessing, model development, training, evaluation, and performance analysis using TensorFlow/Keras.

---

# 📊 Dataset

**Dataset Name:** MNIST Handwritten Digits Dataset

**Source:** Kaggle

**Dataset Link:** https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

> **Note:** The dataset is not included in this repository. Download it from the above link and place it inside a local `dataset/` folder before running the notebook.

---

# 📚 Libraries Used

* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow / Keras

---

# ⚙️ Methodology

1. Load the MNIST dataset.
2. Understand the dataset by displaying records and summary information.
3. Check for missing values.
4. Separate input features and target labels.
5. Normalize pixel values to the range 0–1.
6. Split the dataset into training and testing sets (80:20).
7. Apply One-Hot Encoding to the target labels.
8. Build an Artificial Neural Network (ANN).
9. Train the model for 10 epochs.
10. Predict handwritten digits on the test dataset.
11. Evaluate the model using test accuracy, confusion matrix, and classification report.
12. Visualize model performance using Accuracy vs Epoch and Loss vs Epoch graphs.

---

# 🏗️ Model Architecture

| Layer          | Configuration        |
| -------------- | -------------------- |
| Input Layer    | 784 Input Features   |
| Hidden Layer 1 | 128 Neurons (ReLU)   |
| Hidden Layer 2 | 64 Neurons (ReLU)    |
| Output Layer   | 10 Neurons (Softmax) |

**Optimizer:** Adam

**Loss Function:** Categorical Crossentropy

**Evaluation Metric:** Accuracy

**Epochs:** 10

---

# 📈 Results

* Successfully trained an Artificial Neural Network on the MNIST dataset.
* Achieved high handwritten digit classification accuracy.
* Generated:

  * Test Accuracy
  * Confusion Matrix
  * Classification Report
  * Accuracy vs Epoch Graph
  * Loss vs Epoch Graph

---

# 📝 Conclusion

The Artificial Neural Network successfully learned handwritten digit patterns from the MNIST dataset and achieved excellent classification performance. The hidden layers enabled the model to extract meaningful features, significantly improving prediction accuracy. Deep Learning offers automatic feature extraction, making it more effective than many traditional machine learning techniques. However, ANN models require larger datasets, more computational resources, and longer training times. Overall, the developed model proved to be accurate, efficient, and suitable for handwritten digit recognition tasks.

---

# 📂 Repository Structure

```text
assignment-8/
│
├── Assignment-8.ipynb
├── README.md
├── .gitignore
└── dataset/          (Local Only - Not Uploaded to GitHub)
```

---

# 🚀 How to Run

1. Clone the repository.
2. Download the MNIST dataset from the Kaggle link.
3. Place the dataset inside the `dataset/` folder.
4. Install the required libraries.
5. Open `Assignment-8.ipynb`.
6. Run all cells sequentially.

---

