# AI Assignment 11 - Image Classification Using Random Forest

## Project Overview

This project demonstrates an image classification system using the Random Forest algorithm. The objective is to classify images into five different categories after applying image preprocessing techniques. GridSearchCV was used to optimize the Random Forest model, and the results were evaluated using several performance metrics. A comparison with an SVM classifier was also included.

---

## Dataset

The dataset contains five image categories:

- Dalmatian
- Dollar Bill
- Pizza
- Soccer Ball
- Sunflower

The images were provided as part of the assignment.

---

## Project Workflow

1. Import required libraries.
2. Extract the dataset.
3. Explore the dataset.
4. Preprocess the images:
   - Load images
   - Resize images
   - Normalize pixel values
   - Flatten image arrays
5. Split the dataset into training and testing sets.
6. Train a Random Forest model using GridSearchCV.
7. Evaluate the model using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix
8. Visualize feature importance.
9. Predict the class of a new image.
10. Compare Random Forest with an SVM classifier.

---

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Pillow (PIL)
- Scikit-learn

---

## Model Performance

### Random Forest

- GridSearchCV Hyperparameter Tuning
- Accuracy: **62.90%**

### SVM

- Accuracy: **70.97%**

The SVM model achieved higher accuracy than the Random Forest model on this dataset.

---

## Files Included

- `AI_Assignment_11_Image_Classification_Random_Forest.ipynb`
- `README.md`
- `AI_Assignment_11_Report.pdf`

---

## How to Run

1. Open the notebook in Google Colab.
2. Upload the `images.zip` dataset.
3. Run all notebook cells in order.
4. Review the generated results and visualizations.

---

## Author

**Mohammed Harkan**