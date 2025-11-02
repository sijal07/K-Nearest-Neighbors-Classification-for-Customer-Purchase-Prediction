# K-Nearest-Neighbors-Classification-for-Customer-Purchase-Prediction







K-Nearest Neighbors (KNN) Classification Project
📌 Project Overview
This project demonstrates the implementation of a K-Nearest Neighbors (KNN) classifier to predict whether a user will purchase a product based on their age and estimated salary. The dataset used is Social_Network_Ads.csv, which contains user information and purchasing behavior.

📂 Files in the Repository
1. KNN.ipynb
A Jupyter Notebook containing the complete implementation of the KNN classifier. The notebook includes:

Data Importing and Preprocessing

Loading the dataset using pandas

Splitting the data into training and test sets

Feature scaling using StandardScaler

Model Training

Initializing and training the KNN classifier with:

n_neighbors=5

metric='minkowski'

p=2 (Euclidean distance)

Model Evaluation

Making predictions on the test set

Comparing predicted vs. actual results

Data Visualization

Plotting the decision boundary and training set results using matplotlib

2. Social_Network_Ads.csv
The dataset used for this project. It contains the following columns:

User ID: Unique identifier for each user

Gender: Gender of the user (Male/Female)

Age: Age of the user

EstimatedSalary: Estimated salary of the user

Purchased: Binary target variable (1 = Purchased, 0 = Not Purchased)

🛠️ Technologies Used
Python 3

Libraries:

numpy

pandas

matplotlib

scikit-learn

📊 Key Steps
1. Data Preprocessing
Features (Age, EstimatedSalary) are scaled to ensure optimal performance of the KNN algorithm.

The dataset is split into:

Training set: 75%

Test set: 25%

2. Model Training
The KNN classifier is trained on the scaled training data.

Hyperparameters:

Number of neighbors: 5

Distance metric: Minkowski (Euclidean)

3. Model Evaluation
Predictions are made on the test set.

Results are visualized using a scatter plot with a decision boundary.

4. Visualization
The decision boundary and training data points are plotted to illustrate how the model classifies users.

🚀 How to Run the Code
Clone the Repository:

bash
git clone <repository-url>
cd <repository-directory>
Install Required Libraries:

bash
pip install numpy pandas matplotlib scikit-learn jupyter
Run the Jupyter Notebook:

bash
jupyter notebook KNN.ipynb
Execute the Cells:

Run each cell in the notebook sequentially to reproduce the results.

📈 Results
The KNN classifier successfully classifies users into two categories:

Not Purchased (Red)

Purchased (Green)

The decision boundary clearly separates the two classes based on age and salary.

📝 Notes
The dataset is synthetic and designed for educational purposes.

The model can be further optimized by tuning hyperparameters (e.g., number of neighbors, distance metric).

