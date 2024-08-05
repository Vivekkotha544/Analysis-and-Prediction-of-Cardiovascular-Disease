## Cardiovascular Disease Prediction Using Machine Learning

### Overview
This project aims to predict the risk of cardiovascular disease (CVD) using various machine learning algorithms. The primary focus is on leveraging data-driven insights to develop a reliable prediction model that can identify individuals at risk of CVD.

### Features
- Data preprocessing and feature selection
- Implementation of various machine learning classifiers
- Model evaluation and optimization
- User-friendly interface for data input and prediction

### Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Flask (for the web interface)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cvd-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd cvd-prediction
   ```
3. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
1. Run the Flask application:
   ```bash
   python app.py
   ```
2. Open your web browser and go to `http://127.0.0.1:5000/`.
3. Enter the required patient data and get the prediction for cardiovascular disease risk.

### Machine Learning Models
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest
- Decision Tree
- Support Vector Machine (SVM)

### Project Structure
- `app.py`: The main Flask application file.
- `models.py`: Contains the machine learning models.
- `preprocessing.py`: Data preprocessing and feature selection.
- `templates/`: HTML templates for the web interface.
- `static/`: Static files (CSS, JS) for the web interface.
- `data/`: Dataset files.

### Results
The Logistic Regression model achieved the highest accuracy of 96.23% with an execution time of 1.09 seconds.

## Contributing

I welcome contributions to improve this project! If you have any suggestions or find any issues, please open an issue or submit a pull request.



