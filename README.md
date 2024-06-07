# Classification of Financial Statements using Random Forest classifier and TF-IDF vectorization

This report presents an analysis of table classification from financial statements using natural language processing (NLP) and machine learning techniques. The objective is to classify financial statements into predefined categories such as Income Statement, Balance Sheets, Cash Flow, Notes, and Others.

## Highlights:

- Successfully implemented table classification solution for financial statements using Random Forest classifier and TF-IDF vectorization.
- Achieved accuracy of 94.5% on the test dataset and cross-validation accuracy of 93.6%.
- Designed a scalable solution capable of processing and classifying large volumes of financial statements with high accuracy.

## Approach:

### Data Preprocessing:
- Dataset consists of financial statements stored in HTML format.
- Python libraries such as BeautifulSoup are used for HTML parsing, and pandas is used for data manipulation.
- Each HTML document is processed to extract textual content from tables, followed by text cleaning steps including digit and punctuation removal, lowercase conversion, stop word removal, and lemmatization.

### Feature Extraction:
- The cleaned text data is vectorized using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
- This technique transforms the text data into numerical features, representing the importance of each word in the corpus relative to each document.

### Model Selection:
- A Random Forest classifier is chosen for its simplicity, scalability, and ability to handle high-dimensional data.

## Model Training and Evaluation:

### Training:
- The Random Forest classifier is trained on TF-IDF transformed features using training data.

### Evaluation:
- The model is evaluated using metrics such as accuracy and classification report, providing insights into its performance on both training and test datasets.
- Additionally, cross-validation is performed to assess the model's generalization across different data subsets.

## Results:

### Accuracy:
- The accuracy of the trained model on the test dataset is calculated, indicating its effectiveness in classifying financial statements into predefined categories.

### Cross-Validation Accuracy:
- Cross-validation results provide insights into the model's generalization performance and stability across different subsets of the data.

### Prediction of Classification Results:
- The model predicts the categories of new financial statements, demonstrating its applicability in real-world scenarios.

## Summary:

The implemented approach demonstrates the effectiveness of machine learning models in classifying financial statements based on their content. By leveraging NLP techniques and Random Forest classifier, this model achieves reliable classification results, enabling efficient statement categorization in financial domain applications.
