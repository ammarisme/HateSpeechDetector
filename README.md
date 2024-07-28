
# Project Summary

This project focuses on developing a Hate Speech Detector using both machine learning and deep learning techniques. The project includes data preprocessing, model training, evaluation, and visualization. The datasets used include labeled data and stop words specific to the Sinhalese language.

---

## Features

### 1. Data Collection and Organization
   - **Datasets**: Contains multiple datasets related to hate speech detection.
     - `ascii_dataset.csv`
     - `labelled_data.csv`
     - `non_stop_stem_sinhalese.csv`
     - `sinhalese_stems.csv`
     - `stop_words.csv`
     - `unicode_dataset.csv`
   - **Preprocessed Data**: Datasets are preprocessed to remove stop words and stem words specific to Sinhalese.

### 2. Data Analysis and Preprocessing
   - **Data Cleaning**: Removes unnecessary characters, stop words, and applies stemming to the data.
   - **Exploratory Data Analysis (EDA)**: Includes steps to understand the distribution and characteristics of the data.

### 3. Machine Learning and Deep Learning Models
   - **Model Development**: Implements various machine learning models and deep learning models for hate speech detection.
   - **Model Evaluation**: Uses metrics like accuracy, precision, recall, and F1 score to evaluate model performance.

### 4. Visualization
   - **Results Visualization**: Visualizes the performance of different models and the distribution of data.
     - `results.ipynb.html`

### 5. Documentation and Reporting
   - **Documentation**: Provides detailed documentation on the implementation and comparison of machine learning vs deep learning in NLP.
     - `Deep Learning Implementation.html`
     - `ML vs DL in NLP.pdf`
   - **Jupyter Notebooks**: Contains Jupyter Notebooks for data analysis, model training, and evaluation.
     - `DeepLearning.ipynb`
     - `notebook.ipynb`

---

## Detailed Explanation

### **Data Collection and Organization**

- **Datasets**:
  - `ascii_dataset.csv`: Contains text data in ASCII format.
  - `labelled_data.csv`: Includes labeled data for training and evaluating models.
  - `non_stop_stem_sinhalese.csv`: Contains Sinhalese text data with stop words removed and words stemmed.
  - `sinhalese_stems.csv`: List of stemmed Sinhalese words.
  - `stop_words.csv`: List of Sinhalese stop words.
  - `unicode_dataset.csv`: Contains text data in Unicode format.

### **Data Analysis and Preprocessing**

- **Data Cleaning**: Involves removing non-alphanumeric characters, stop words, and applying stemming to the text data.
- **Exploratory Data Analysis (EDA)**: Analyzes the data to understand its distribution and key characteristics.

### **Machine Learning and Deep Learning Models**

- **Model Development**: Implements models such as Logistic Regression, SVM, Random Forest, and deep learning models like CNN and RNN.
- **Model Evaluation**: Evaluates models using metrics such as accuracy, precision, recall, and F1 score.

### **Visualization**

- **Results Visualization**: Visualizes the performance of different models using HTML reports and Jupyter Notebooks.
  - `results.ipynb.html`: Contains visualizations of model performance and data distribution.

### **Documentation and Reporting**

- **Documentation**: Provides detailed documentation on the deep learning implementation and comparison with machine learning.
  - `Deep Learning Implementation.html`
  - `ML vs DL in NLP.pdf`
- **Jupyter Notebooks**: Includes notebooks for interactive data analysis and model training.
  - `DeepLearning.ipynb`
  - `notebook.ipynb`

---

## Usage Instructions

1. **Clone the Repository**: 
   ```bash
   git clone <repository-url>
   ```

2. **Install Dependencies**: 
   - Ensure you have Python and required libraries installed. You can install the necessary libraries using:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Jupyter Notebooks**:
   - Open and run `DeepLearning.ipynb` and `notebook.ipynb` to perform data analysis, model training, and evaluation.

4. **Review Results**:
   - Open `results.ipynb.html` to review the visualizations of model performance and data distribution.
   - Refer to `Deep Learning Implementation.html` and `ML vs DL in NLP.pdf` for detailed documentation.

---

## Conclusion

This project provides a comprehensive approach to hate speech detection using both machine learning and deep learning techniques. It includes detailed documentation, data preprocessing, model training, evaluation, and visualization to offer valuable insights into the effectiveness of different approaches in NLP for hate speech detection.
