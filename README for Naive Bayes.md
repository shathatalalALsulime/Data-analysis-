## Heart Disease Classification using Naive Bayes

### Project Description
This project aims to classify heart disease using the Naive Bayes model. It analyzes data available in the `heart.csv` file, which contains information on various factors related to heart health.

### Requirements
Make sure to install the following libraries:
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`

You can install the required libraries using:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

### Data
The data is available in the `heart.csv` file, which contains the following columns:
- `age`: Age of the patient
- `sex`: Gender (0 = female, 1 = male)
- `cp`: Chest pain type
- `trestbps`: Resting blood pressure
- `chol`: Cholesterol level
- `fbs`: Fasting blood sugar
- `restecg`: Resting electrocardiographic results
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise induced angina
- `oldpeak`: ST depression
- `slope`: Slope of the ST segment
- `ca`: Number of major vessels colored by fluoroscopy
- `thal`: Thalassemia status
- `target`: Presence of heart disease (0 = no, 1 = yes)

### How to Use
1. **Import Libraries**: Import the necessary libraries in your code.
2. **Load Data**: Use `pandas` to load the data from the `heart.csv` file.
3. **Explore Data**: Display the shape and basic statistics of the dataset.
4. **Visualize Data**: Perform visual analysis on the distribution of the target variable.
5. **Split Data**: Divide the data into training and testing sets.
6. **Build Model**: Use the Naive Bayes model to train and evaluate its performance.

### Running the Code
You can run the code in an environment such as Jupyter Notebook or Google Colab. Execute the cells in sequence to obtain results.

### Contribution
If you would like to contribute to this project, feel free to open issues or submit pull requests.
