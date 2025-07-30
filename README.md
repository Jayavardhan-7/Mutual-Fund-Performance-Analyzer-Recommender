# Mutual Fund Performance Analyzer & Risk-Based Recommender

This project is a Flask-based web application that allows users to analyze the performance of mutual funds and receive risk-based recommendations.

## Features

- **Mutual Fund Performance Analysis**: Enter a mutual fund name to get a placeholder performance analysis.
- **Risk-Based Recommendations**: Select your risk tolerance (Low, Medium, High) to receive placeholder mutual fund recommendations.

## Setup Instructions

Follow these steps to set up and run the application locally:

1.  **Navigate to the project directory**:
    ```bash
    cd mutual_fund_analyzer
    ```

2.  **Activate the virtual environment**:
    ```bash
    .\venv\Scripts\activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install Flask requests
    ```

4.  **Run the Flask application**:
    ```bash
    python app.py
    ```

5.  **Access the application**: Open your web browser and go to `http://127.0.0.1:5000/`.

## Project Structure

```
mutual_fund_analyzer/
├── venv/                   # Python virtual environment
├── static/                 # Static files (CSS, JS)
│   ├── style.css
│   └── script.js
├── templates/              # HTML templates
│   └── index.html
├── app.py                  # Main Flask application file
└── README.md               # This README file
```

## Future Enhancements

-   Integrate with real-time mutual fund data APIs.
-   Implement actual performance calculation and risk assessment models.
-   Develop a more sophisticated risk-based recommendation engine.
-   Add user authentication and personalized portfolios.
-   Improve UI/UX with more interactive charts and data visualizations.