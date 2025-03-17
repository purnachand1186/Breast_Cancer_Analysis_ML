### Breast Cancer Analysis and Identification

#### Executive summary

This capstone project aims to leverage the UC Irvine breast cancer dataset to evaluate and enhance the predictive capabilities of the Machine Learning algorithms, trying the data with a deep learning model designed to assess breast cancer risk from mammogram images. The project focuses on analyzing the data, data cleaning, reducing false positives and negatives, and ensuring equitable healthcare outcomes across diverse populations.

### Goals

**Data Preprocessing:**

Utilize the UC Irvine breast cancer dataset or Seaborn Breast Cancer data, which includes features such as tumor size, shape, and other relevant attributes and
create new features or transform existing ones to improve the predictive power of the models.

**Exploratory Data Analysis (EDA):**

Use various visualization techniques to understand the distribution of features and identify patterns or correlations and perform statistical analysis to gain insights into the relationships between different features and the target variable.

**Model Training and Evaluation:**

Experiment with different machine learning algorithms such as Logistic Regression, Decision Trees, Random Forests, and Support Vector Machines (SVM), use techniques like GridSearchCV to optimize the hyperparameters of the models.


#### Data Sources
In this application, I will explore the Breast Cancer dataset from the UC Irvine dataset ( https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic). The same dataset is available in the Python SNSN module. The goal of this project is to perform EDA on the data, perform analysis, and predict malignant patients using the information provided.

Dataset Information

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe the characteristics of the cell nuclei present in the image. A few of the images can be found at http://www.cs.wisc.edu/~street/images/

Separating plane described above was obtained using Multisurface Method-Tree (MSM-T) [K. P. Bennett, "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992], a classification method which uses linear programming to construct a decision tree. Relevant features were selected using an exhaustive search in the space of 1-4 features and 1-3 separating planes.

The actual linear program used to obtain the separating plane in the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This database is also available through the UW CS ftp server: ftp ftp.cs.wisc.edu cd math-prog/cpo-dataset/machine-learn/WDBC/

Attribute Information:

ID number

Diagnosis (M (0) = malignant, B (1) = benign) 3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from the center to points on the perimeter)

b) texture (standard deviation of gray-scale values)

c) perimeter

d) area

e) smoothness (local variation in radius lengths)

f) compactness (perimeter^2 / area - 1.0)

g) concavity (severity of concave portions of the contour)

h) concave points (number of concave portions of the contour)

i) symmetry

j) fractal dimension ("coastline approximation" - 1)

Class distribution: 357 benign, 212 malignant

#### Methodology
Data Collection and Preprocessing: Gather and preprocess mammogram images and associated clinical data from the UC Berkeley dataset (Seaborn Breast Cancer dataset), data was cleaned, and outliers were removed from a few columns. 


Algorithm Training and Validation: Train the Mirai algorithm on the dataset and validate its performance using cross-validation techniques.

Statistical Analysis: Conduct statistical analyses to identify key predictive factors and assess the algorithm's performance across different subgroups.

Algorithm Enhancement: Implement and test modifications to the algorithm to improve its accuracy and reliability.

Outcome Evaluation: Evaluate the impact of the enhanced algorithm on early detection rates and health equity.

#### Results
Accuracy: Achieve High Accuracy in terms of predictability from the available ML models

