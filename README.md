# Prediction of Plug length of Founded Pile
***Problem Statement***
Pile driving is a complex process involving unexpected soil conditions, pile damages, pile alignment issues, driving systems, and data acquisition mechanisms. Though there are several methods to test and predict the soil properties and hammer blow counts, the drivability conditions experienced by open-ended hollow piles are still an uncertain aspect of the pile foundation industry. When driven using a pile driving system, the soil penetrates inside the hollow pile shaft leading to plugging.
The pile plugging leads to a greater increase in soil resistance than anticipated through soil analysis and dynamic measurements. However, there is still a lack of understanding about pile plugging and estimation of pile capacity.

***Objectives****
The present study focuses on assessing the plugging mechanism of modelled pile in laboratory and field conditions. Scaled aluminium hollow piles sections of different diameters are driven using impact loads simulating the Standard Penetration Test.
The resulting blow counts, plugged length and soil density developed inside the pile shaft are estimated through laboratory and field investigations. It is observed that there is a high correlation between field data and experimental studies, and the plugging mechanism exhibited an inverse relationship with pile geometrics.


****ML Model Building***
A General outline of how predictive learning techniques is utilized:

Data Collection: Gathered a dataset containing information about pile installations, soil properties, pile geometry, driving conditions, and other relevant parameters. This dataset should include instances where pile plugging has occurred and instances where it has not.

Feature Selection: Identified the most relevant features or parameters that may influence pile plugging behavior. These features could include soil type, pile geometry, driving method, penetration resistance, or any other factors that are believed to impact pile plugging.

Data Preprocessing: Cleaned the dataset by handling missing values, normalizing or standardizing the features, and encoding categorical variables if necessary.

Model Training: Selected an regression machine learning algorithm based on the nature of the problem and available data. Split the dataset into training and testing sets.

Model Training and Evaluation: Trained the selected model using the training dataset and evaluate its performance using appropriate evaluation metrics, such as accuracy, precision, recall, or F1 score. Adjust the model parameters or try different algorithms if necessary to improve performance.

Prediction and Interpretation: Once the model is trained and evaluated, it is used to predict pile plugging behavior for new instances or unseen data. Interpret the model's predictions to gain insights into the factors that contribute to pile plugging and their relative importance.

Model Validation: Validated the trained model using additional datasets or real-world observations to assess its generalizability and robustness.

By applying predictive learning techniques, it is possible to develop models that can predict the likelihood of pile plugging based on input parameters. These models can assist in optimizing pile design, construction methods, and maintenance strategies to mitigate the risk of pile plugging and improve the overall performance of pile foundations.


