# Social Media Addiction During Lockdown - Machine Learning Project

## Project Overview
This project analyzes social media addiction patterns during the COVID-19 lockdown period using survey data. The aim is to build a machine learning model to uncover behavioral patterns and predict addiction tendencies based on various features.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Optimizations](#optimizations)
- [Contributing](#contributing)
- [License](#license)

---

## Dataset
The dataset contains responses from individuals regarding their social media usage during the lockdown. It includes various features such as demographics, time spent on social media, and self-reported addiction levels.

**Target Variable:**
- `Addiction Level` (categorical or numerical depending on project approach)

**Sample Features:**
- Age
- Gender
- Time spent on social media
- Preferred social media platforms
- Emotional impact

---

## Features
- Data loading and exploratory analysis
- Data cleaning (removal of timestamp and redundant columns)
- Feature engineering and encoding
- Model training and evaluation
- Visualization of trends and insights

---

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-Learn

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/social-media-addiction.git
   cd social-media-addiction
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place your dataset CSV file in the project directory.

---

## Usage
1. Open the notebook `SOCIAL_MEDIA_ADDICTION_DURING_LOCKDOWN_ML_PROJECT_G5.ipynb`.
2. Run the cells sequentially to preprocess the data, train the model, and visualize insights.
3. Modify hyperparameters or model types if needed.

---

## Results
Initial results indicate that the model achieved the following performance metrics:
- Accuracy: 35%
- Precision: 35%
- Recall: 35%

Further optimization is suggested to improve model performance.

---

## Optimizations
1. **Data Handling:**
   - Avoid reading the CSV file multiple times; read once and reuse the DataFrame.
2. **Feature Engineering:**
   - Explore feature importance to drop irrelevant features.
3. **Pipeline Creation:**
   - Integrate preprocessing and model training into a Scikit-Learn pipeline for cleaner and more maintainable code.
4. **Cross-Validation:**
   - Use cross-validation (`cross_val_score`) for model stability.

---

## Contributing
Contributions are welcome. Please create a pull request or open an issue for discussion.

---

## License
This project is licensed under the [MIT License](LICENSE).

