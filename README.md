# Text-Classification-using-Logistic-Regression
This repository contains the solution for an NLP problem focused on implementing a binary text classification task to detect hallucinations in summaries using Logistic Regression.

## Project Description
The goal of this project is to build a **binary hallucination detection classifier** to determine whether a given text (summary) is hallucinated or factual. The solution involves implementing Logistic Regression from scratch, without libraries, and evaluating its performance using various metrics and methods.

## Dataset
The [XSum Hallucination dataset](https://github.com/google-research-datasets/xsum_hallucination_annotations/blob/master/factuality_annotations_xsum_summaries.csv) is used for this project. It includes:
- **Input Text:** `summary`
- **Label:** `is_factual` (absence of hallucination)

## Tasks Completed
1. **Data Preprocessing:** 
   - Cleaned and tokenized text data for model training.
   - Transformed text into numerical format for regression analysis.
   
2. **Model Training:** 
   - Implemented Logistic Regression from scratch.
   - Trained the model on the dataset and tuned hyperparameters.
   
3. **Model Evaluation:** 
   - Evaluated using accuracy, precision, recall, and F1 score.
   - Visualized the model's performance using a confusion matrix.
   
4. **Cross-Validation:**
   - Performed k-fold cross-validation to assess model robustness.
   - Reported the average accuracy and standard deviation across folds.
   
5. **Error Analysis:**
   - Identified misclassified examples.
   - Provided insights and suggestions for model improvements.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Zain-Rizwan/Text-Classification-using-Logistic-Regression.git
