# Auto MPG Analysis and Prediction

This project focuses on analyzing and modeling fuel efficiency (measured in miles per gallon - MPG) for various car models using the well-known Auto MPG dataset provided by Seaborn.

## Project Goals

- Perform exploratory data analysis (EDA) on the Auto MPG dataset
- Preprocess the data: handle missing values, encode categorical variables, normalize features
- Build and evaluate a regression model to predict MPG based on vehicle attributes

## Technologies Used

- Python (Jupyter Notebook)
- Pandas
- Seaborn
- Scikit-learn
- Matplotlib
- NumPy

## Notebook Structure

1. **Data Loading**
   - Dataset source: `seaborn.load_dataset('mpg')`
   - Initial inspection (`head()`, `describe()`, `info()`)

2. **Exploratory Data Analysis (EDA)**
   - Visualizations of relationships between features
   - Distribution analysis (e.g., horsepower, weight, acceleration)

3. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling and selection

4. **Modeling**
   - Regression modeling (e.g., Linear Regression, Random Forest)
   - Model evaluation metrics: R², RMSE, MAE

5. **Conclusions**
   - Key factors influencing MPG
   - Model performance and potential improvements

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mpg_project.git
   cd mpg_project
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook MPG_Project.ipynb
   ```

## Dataset Source

The `mpg` dataset is available from:
[https://github.com/mwaskom/seaborn-data](https://github.com/mwaskom/seaborn-data)

## Author

Created by Marcin Mikos

## License

This project is licensed under the MIT License.
