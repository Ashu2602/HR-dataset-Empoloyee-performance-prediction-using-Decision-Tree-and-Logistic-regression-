**Google Collab link** : https://colab.research.google.com/drive/1pqdPamU064LwgrWZlJLQC0m2zq9gUZ4G#scrollTo=Xn5RZS5f-xas
HR Performance Prediction Project
This project aims to predict employee performance scores based on a Human Resources dataset. The dataset contains various employee-related features such as marital status, salary, special projects count, engagement survey results, and more. The goal is to develop machine learning models that can accurately predict an employee's performance score using these attributes.

Project Overview
The project is organized into several stages:

Data Import and Exploration: In this stage, we import the necessary Python libraries for data manipulation and visualization. We load the HR dataset ('HRDataset_v14.csv') into the system using Pandas and perform an initial exploration of the dataset to understand its structure. We check for missing values and handle them appropriately. Additionally, we remove date columns that are not relevant to the prediction.
Dataset Initial Look:
![dataset first five columns pandas ](https://github.com/Ashu2602/HR-dataset-Empoloyee-performance-prediction-using-Decision-Tree-and-Logistic-regression-/assets/72691272/f1769921-5969-4dd4-94e6-118aee532dbf)

![Dataset intialization](https://github.com/Ashu2602/HR-dataset-Empoloyee-performance-prediction-using-Decision-Tree-and-Logistic-regression-/assets/72691272/654b46d0-b69c-4c6d-9c89-280b6d109aa0)
Checking for null values  and dropping columns :
![Checking count of null values after dropping column and filling missing values ](https://github.com/Ashu2602/HR-dataset-Empoloyee-performance-prediction-using-Decision-Tree-and-Logistic-regression-/assets/72691272/d627f432-2568-4d33-87e4-b8e155354fd5)


Data Visualization and Analysis: We use Seaborn and Matplotlib to visualize the data, gaining insights into the relationships between features. We create correlation matrices and scatter plots to identify potential patterns and correlations. We also explore the distribution of the target variable 'PerformanceScore' using count plots.
![Dataset intialization](https://github.com/Ashu2602/HR-dataset-Empoloyee-performance-prediction-using-Decision-Tree-and-Logistic-regression-/assets/72691272/e4b05afe-87a4-476c-ab1e-301d4c5d17d3)
![Scatter plot of performance score and salary ](https://github.com/Ashu2602/HR-dataset-Empoloyee-performance-prediction-using-Decision-Tree-and-Logistic-regression-/assets/72691272/5fa53cf5-abfc-452e-a6a4-36c6786cbd5f)
![Scatter plot performance score and Engagement Survey ](https://github.com/Ashu2602/HR-dataset-Empoloyee-performance-prediction-using-Decision-Tree-and-Logistic-regression-/assets/72691272/fcf1ccca-6570-4460-96ff-d50e5ba37c2f)




Data Preprocessing: In this stage, we preprocess the data by encoding categorical features using Label Encoding if needed. We split the data into features (X) and the target variable (y) and further split the dataset into training and testing sets using the train_test_split function.
![PerfscoreID](https://github.com/Ashu2602/HR-dataset-Empoloyee-performance-prediction-using-Decision-Tree-and-Logistic-regression-/assets/72691272/93341316-8815-4252-8156-9c5329c96b34)
Manager name Missing value replaced :
![Manager name missing values replacesd](https://github.com/Ashu2602/HR-dataset-Empoloyee-performance-prediction-using-Decision-Tree-and-Logistic-regression-/assets/72691272/f6b95b3d-7a90-44e4-9928-33e03dba245f)

Difference between the multiclass values in the data :
![boxplot of different classes with the no of employees](https://github.com/Ashu2602/HR-dataset-Empoloyee-performance-prediction-using-Decision-Tree-and-Logistic-regression-/assets/72691272/1c968d40-1b65-4998-bf57-5dbcee887fd9)


Model Building: We train a Decision Tree Classifier and a Logistic Regression model to predict employee performance. We evaluate both models using accuracy, precision, recall, and the confusion matrix to assess their performance.

Decision Tree Visualization: We visualize the Decision Tree Classifier to gain insights into how the model makes predictions. This step helps us interpret the model's decision-making process.
Decision Tree 
![Decision tree V2](https://github.com/Ashu2602/HR-dataset-Empoloyee-performance-prediction-using-Decision-Tree-and-Logistic-regression-/assets/72691272/fdb75de4-bc34-4941-b1d5-0e76e5ad9590)

Model Fine-Tuning: To optimize the Decision Tree Classifier, we experiment with different hyperparameters and use techniques like GridSearchCV for hyperparameter tuning. This step aims to improve the model's predictive performance.


Conclusion and Next Steps: We summarize the results and findings from the different models, discussing their respective strengths and weaknesses. We also suggest potential next steps for further improvements, such as feature engineering or the exploration of additional data sources. This section provides a comprehensive overview of the project's goals and achievements.

Documentation: In the documentation section, you'll find all the necessary instructions for running the code and replicating the project. We also share relevant insights and observations made during the project.

How to Use This Project
Clone this repository to your local machine using the following command:

bash
Copy code
git clone https://github.com/your-username/hr-performance-prediction.git
Install the required Python libraries if you haven't already. You can use the following command to install them using pip:

Copy code
pip install -r requirements.txt
Run the Jupyter Notebook files in the project directory to follow the project stages and explore the code and results.

Feel free to experiment with different models, hyperparameters, and data preprocessing techniques to further enhance the predictive performance.

Refer to the documentation section for additional details and insights obtained from the project.

Contributors
Your Name - Ashutosh misra
License

Acknowledgments
This project was inspired by the need to improve HR decision-making through predictive analytics.
Special thanks to the open-source community for providing valuable tools and libraries.
Thank you for using and contributing to the HR Performance Prediction Project! If you have any questions or feedback, please don't hesitate to reach out to the project lead or open an issue on GitHub.



