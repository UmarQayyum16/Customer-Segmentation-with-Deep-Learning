# Customer Segmentation Project

## Overview

This project focuses on customer segmentation using deep learning techniques. The primary goal is to understand and group customers based on their behavior and characteristics. The project involves exploratory data analysis (EDA), data preprocessing, model development, and evaluation.

## Dataset

The dataset used for this project is sourced from [HackerEarth HackLive: Customer Segmentation](https://www.kaggle.com/dataset_name) on Kaggle. It includes information about customer demographics, interactions, and subscription status.

### Data Columns

- **id:** Customer identifier
- **customer_age:** Age of the customer
- **job_type:** Type of job
- **marital:** Marital status
- **education:** Education level
- **default:** Whether the customer has credit in default (yes/no)
- **balance:** Customer's account balance
- **housing_loan:** Has a housing loan? (yes/no)
- **personal_loan:** Has a personal loan? (yes/no)
- **communication_type:** Type of communication for the last contact
- **day_of_month:** Day of the month when the last contact was made
- **month:** Month when the last contact was made
- **last_contact_duration:** Duration of the last contact in seconds
- **num_contacts_in_campaign:** Number of contacts performed during the campaign
- **days_since_prev_campaign_contact:** Days since the previous campaign contact
- **num_contacts_prev_campaign:** Number of contacts performed in the previous campaign
- **prev_campaign_outcome:** Outcome of the previous marketing campaign
- **term_deposit_subscribed:** Binary variable indicating whether the customer subscribed to a term deposit (1) or not (0)

## Project Workflow

1. **Exploratory Data Analysis (EDA):**
   - Understand the structure of the dataset.
   - Handle missing values and outliers.
   - Visualize key features for insights.

![visualize_outliers](https://github.com/UmarQayyum16/Customer-Segmentation-with-Deep-Learning/assets/149918632/35c0f1f8-e21b-4616-9307-09b3daca54a3)
![correlation_matrix](https://github.com/UmarQayyum16/Customer-Segmentation-with-Deep-Learning/assets/149918632/96a8843b-c62c-4a76-8d5a-b3aabc4ffcaa)


2. **Data Preprocessing:**
   - Handle categorical variables.
   - Address missing values through imputation.
   - Scale numerical features.
     
![scaled](https://github.com/UmarQayyum16/Customer-Segmentation-with-Deep-Learning/assets/149918632/c47d681f-01c6-4141-9cd9-9eac5f1d4848)

3. **Model Development:**
   - Split the dataset into training and testing sets.
   - Implement oversampling techniques to address class imbalance.
   - Build a neural network model using TensorFlow/Keras.
   - Compile and train the model.
     
![model_architecture](https://github.com/UmarQayyum16/Customer-Segmentation-with-Deep-Learning/assets/149918632/1f0b6657-1613-4544-8a58-1793801ab880)

4. **Model Evaluation:**
   - Evaluate the model using metrics such as accuracy, precision, recall, and F1-score.
   - Visualize the training process using TensorBoard.
   - Save the trained model for future use.

![training_process_epoch_loss](https://github.com/UmarQayyum16/Customer-Segmentation-with-Deep-Learning/assets/149918632/917f2fc2-2237-4e43-9d2c-96d44d1a96e5)
![training_process_epoch_accuracy](https://github.com/UmarQayyum16/Customer-Segmentation-with-Deep-Learning/assets/149918632/1ecbe407-81d8-412e-b5c1-ccc8b3620be2)
![classification_report](https://github.com/UmarQayyum16/Customer-Segmentation-with-Deep-Learning/assets/149918632/ae155e19-73e3-4bce-9af0-c9fe3ccf2303)
![confusion_matrix](https://github.com/UmarQayyum16/Customer-Segmentation-with-Deep-Learning/assets/149918632/e7de4b01-d17e-443e-b6f3-751feada5b5b)

After training and testing the model, here are the evaluation metrics:

- **Test Loss:** 0.3063
- **Test Accuracy:** 87.91%

These metrics provide insights into how well the model performs on unseen data. A lower test loss indicates better performance, and the test accuracy shows the percentage of correctly classified instances in the test set.

## Conclusion

The customer segmentation model developed in this project provides insights into customer behavior and aids in targeted marketing efforts. By understanding distinct customer segments, businesses can tailor their strategies to enhance customer satisfaction and maximize returns.

Feel free to explore the code and adapt it for your specific needs. Contributions and suggestions are welcome!
