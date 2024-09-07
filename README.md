# PROJECTEXPO
Here's a README file template for your medical insurance price prediction project using a Linear Regression model. You can adjust the details according to your specific implementation and requirements.

---

# Medical Insurance Price Prediction

## Project Overview

This project aims to predict medical insurance charges based on various factors such as age, gender, BMI, number of children, smoking status, and region. A Linear Regression model is used for this purpose, and the project involves preprocessing the data, training the model, evaluating its performance, and making predictions on new data.

## Dataset

The dataset used for this project is `insurance_large.csv`, which includes the following columns:
- `age`: Age of the individual.
- `gender`: Gender of the individual (`male` or `female`).
- `bmi`: Body Mass Index of the individual.
- `children`: Number of children/dependents of the individual.
- `smoker`: Whether the individual is a smoker (`yes` or `no`).
- `region`: The region where the individual lives (`southeast`, `northwest`, `northeast`, `southwest`).
- `charges`: Medical insurance charges (the target variable).

### Sample Data (First 10 Rows)

age	gender	bmi	children	smoker	region	charges
19	female	27.9	0	yes	southwest	16884.924
18	male	33.77	1	no	southeast	1725.5523
28	male	33	3	no	southeast	4449.462
33	male	22.705	0	no	northwest	21984.47061
32	male	28.88	0	no	northwest	3866.8552
31	female	25.74	0	no	southeast	3756.6216
46	female	33.44	1	no	southeast	8240.5896
37	female	27.74	3	no	northwest	7281.5056
37	male	29.83	2	no	northeast	6406.4107


## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/insurance-price-prediction.git
   cd insurance-price-prediction
   ```

2. **Install Dependencies:**
   Ensure you have Python installed, then install the necessary Python packages using `pip`:
   ```bash
   pip install pandas numpy scikit-learn
   ```

3. **Download the Dataset:**
   Make sure the `insurance_large.csv` file is placed in the same directory as the Python script.

## Usage

1. **Run the Prediction Script:**
   Execute the script to train the model and make predictions:
   ```bash
   python predict_insurance.py
   ```

2. **Input New Data:**
   To predict insurance charges for new data, modify the `predict_new_price` function in `predict_insurance.py` with your input values.

## Code Explanation

- **Data Preprocessing:**
  - Categorical variables are encoded using `LabelEncoder`.
  - Features are normalized using `StandardScaler`.

- **Model Training:**
  - A Linear Regression model is created and trained using the training dataset.

- **Evaluation:**
  - Model performance is evaluated using Mean Squared Error (MSE) and R-squared score (R²).

- **Prediction:**
  - The trained model predicts insurance charges based on new input data.

## Example

To predict the insurance price for a new individual with the following details:
- Age: 35
- Gender: male
- BMI: 24.0
- Children: 2
- Smoker: yes
- Region: southeast

Update the `predict_new_price` function and run the script to get the predicted price.
## Screenshot of output 


![medicalinsurancepp](https://github.com/user-attachments/assets/cda2efe5-6493-4b3e-9733-5c442e925e59)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please contact (mailto:  kyogitha801@gmail.com).

---

