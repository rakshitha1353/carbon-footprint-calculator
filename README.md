## carbon-footprint-calculator


## Description

This project is a Carbon Footprint Calculator, a command-line application designed to estimate your annual carbon footprint using machine learning. By inputting data about your daily activities, such as energy consumption, transportation habits, and dietary choices, the application provides a personalized estimate of your environmental impact. It also offers actionable recommendations and solutions to help you reduce your carbon footprint.

## Key Features

* **Machine Learning Prediction:** Uses a RandomForestRegressor model to predict total carbon footprint based on user inputs.
* **Detailed Breakdown:** Generates a pie chart visualizing the distribution of emissions across different categories (commercial, transport, software/device runtime, flight, food, home energy).
* **Personalized Recommendations:** Provides tailored recommendations and solutions based on your activity levels, encouraging sustainable practices.
* **User-Friendly Input:** Simple command-line interface for easy data entry.

## Technologies Used

* **Python:** Core programming language for data processing, machine learning, and calculations.
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical computations.
* **Scikit-learn:** For machine learning (RandomForestRegressor).
* **Matplotlib:** For data visualization (pie chart).

## Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/rakshitha1353/carbon-footprint-calculator
    
    ```

2.  **Install dependencies:**

    ```bash
    pip install pandas numpy scikit-learn matplotlib
    ```

## Usage

1.  **Run the script:**

    ```bash
    python carbon_footprint_calculator.py
    ```

2.  **Follow the prompts:** Enter your activity levels for each category when prompted.

3.  **View results:** The application will display your estimated carbon footprint, a pie chart breakdown, and personalized recommendations.

## Model Details

* **Model:** RandomForestRegressor with 100 estimators.
* **Training Data:** The model is currently trained on synthetic data for demonstration purposes. For accurate real-world predictions, it should be trained on real-world data.
* **Emission Factors:** The `emission_factors` dictionary contains example values. These values should be replaced with accurate and up-to-date emission factors for precise calculations.

## Recommendations and Solutions Logic

The application provides recommendations based on predefined activity level ranges. These recommendations are designed to offer practical steps for reducing carbon emissions.

## Future Improvements
* **Enhanced Emission Factors:** Use accurate and updated emission factors.
* **Model Evaluation:** Implement model evaluation metrics (e.g., R-squared, MAE) to assess performance.
* **Data Persistence:** Implement a database or file system for storing user data and model parameters.
* **User Interface:** Develop a graphical user interface (GUI) or web interface for a more user-friendly experience.
* **Improved Recommendation Logic:** Create a more dynamic and adaptable recommendation system.
* **Add unit testing:** Add unit testing to the project.

## Author

Rakshitha G

* Email: rakshitha.g.blr@gmail.com
* LinkedIn: https://www.linkedin.com/in/rakshitha-g1/
* GitHub: https://github.com/rakshitha1353/

## License

This project is licensed under the MIT License.
