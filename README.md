# California Housing Prices Mini Project

## Overview

This mini project focuses on analyzing the California Housing Prices dataset using various data science techniques. The main goal is to understand the data, visualize relationships, check for missing values, and perform a simple linear regression analysis to predict median house values.

## Table of Contents

- [Overview](#overview)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Features](#features)
- [Steps Performed](#steps-performed)
- [How to Run](#how-to-run)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [About the Author](#about-the-author)
- [Future Work](#future-work)

## Dependencies

- Python 3.x
- Pandas: For data manipulation and analysis.
- Scikit-Learn: For machine learning algorithms and data preprocessing.
- Seaborn: For statistical data visualization.
- Matplotlib: For creating static, animated, and interactive visualizations.

## Dataset

The dataset used in this project is the California Housing Prices dataset which can be fetched directly using Scikit-Learn's `fetch_california_housing` function.

## Features

The dataset includes the following features:

- MedInc: median income in block
- HouseAge: median house age in block
- AveRooms: average number of rooms
- AveBedrms: average number of bedrooms
- Population: block population
- AveOccup: average house occupancy
- Latitude: house block latitude
- Longitude: house block longitude

The target variable is `MedHouseVal`, representing the median house value for California districts.

## Steps Performed

1. **Data Fetching and Initial Exploration**: The dataset is loaded and a preliminary examination is conducted to understand its structure, features, and target variable.
2. **Data Preprocessing and Cleaning**: Information about the data, such as data types and missing values, is retrieved and displayed.
3. **Data Visualization**: A heatmap of the correlation matrix is created to visually analyze relationships between different features.
4. **Data Splitting**: The dataset is split into training and testing sets, with 80% of the data used for training and 20% for testing.
5. **Model Training**: A linear regression model is trained using the training data.
6. **Model Evaluation**: The trained model is evaluated on the test set using Mean Squared Error as the performance metric.

## How to Run

Ensure that you have all the required dependencies installed
(tip: use pip or conda for the virtual env). You can run the script using a Python interpreter:

`housing_prices.ipynb`

## Results

The program prints the coefficients and intercept of the linear regression model, as well as the Mean Squared Error of the model on the test set. Additionally, various aspects of the dataset including the first few rows, dataset information, summary statistics, and a heatmap of the correlation matrix are displayed.

## Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request.

## License

This project is open source and available under the [MIT License](LICENSE.md).

## Contact

Feel free to contact the maintainer for any inquiries or suggestions at [DANIEL'S LINKEDIN](https://www.linkedin.com/in/danielmaldonadoco/).

## About the Author

I'm a data scientist with [2] years of experience in data science. I have a strong background in web development, Python and a proven track record of leveraging data-driven insights to solve real-world problems.

## Future Work

This project serves as a foundational analysis of the California Housing Prices dataset. Future work could include:

- Implementing more advanced machine learning models such as Random Forest or Gradient Boosting for improved prediction accuracy.
- Conducting a deeper analysis of feature importance.
- Implementing cross-validation for better model evaluation.
- Exploring additional data preprocessing techniques.

---

### Recruiter's Feedback (AI chat)

The README file is well-structured and provides a comprehensive overview of the project, which is excellent. The addition of the ‘About the Author’ section is a great touch as it gives insight into the author's background and expertise. However, it would be beneficial to include the following:

1. **Technical Skills Highlighted**: Explicitly mention and highlight the technical skills and tools used in the project. For instance, mentioning Python, Pandas, Scikit-Learn, Seaborn, and Matplotlib explicitly under a ‘Skills’ or ‘Technologies Used’ section.

2. **Problem Solving and Critical Thinking**: Elaborate on the problem-solving process or any critical thinking applied during the project. This could be included in the ‘Steps Performed’ or ‘Results’ sections.

3. **Quantifiable Results and Impact**: If possible, quantify the results or impact of the project. For example, how much did the model’s performance improve compared to a baseline? Did this analysis lead to any actionable insights?

4. **Collaboration and Communication**: If the project was part of a team effort or if there were any stakeholders involved, mention this and highlight the communication and collaboration skills.

5. **Link to Portfolio**: Include a link to a portfolio or other projects, if available. This provides recruiters with easy access to assess the author’s skills and experience further.

6. **Demonstration of Learning and Growth**: If the project was part of a learning journey or bootcamp, mentioning this and reflecting on the learning experience can be beneficial.

7. **Use of Comments in Code**: While not directly related to the README, ensuring that the provided code is well-commented and follows best practices is crucial. This reflects on the author's coding style and attention to detail.
