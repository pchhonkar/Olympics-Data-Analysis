<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Olympics Data Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f9;
            color: #333;
        }
        h1, h2, h3 {
            color: #0056b3;
        }
        pre {
            background: #f4f4f4;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            overflow-x: auto;
        }
        code {
            font-family: "Courier New", Courier, monospace;
            color: #d63384;
        }
        ul {
            margin: 10px 0;
            padding-left: 20px;
        }
        a {
            color: #0056b3;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .btn {
            display: inline-block;
            background: #0056b3;
            color: white;
            padding: 10px 15px;
            border-radius: 5px;
            text-decoration: none;
            margin: 10px 0;
        }
        .btn:hover {
            background: #004085;
        }
        .code-block {
            background: #2d2d2d;
            color: #f8f8f2;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <h1>Olympics Data Analysis</h1>
    <p>Welcome to the <strong>Olympics Data Analysis</strong> project! This project leverages <strong>Streamlit</strong> to explore, analyze, and visualize Olympics data interactively, using powerful Python libraries and Machine Learning techniques to extract meaningful insights.</p>
    
    <h2>Project Overview</h2>
    <p>This project aims to analyze Olympics data and uncover trends, patterns, and key insights using advanced visualization and predictive modeling. The interactive Streamlit dashboard provides tools for users to explore:</p>
    <ul>
        <li><strong>Trends in Olympic Data</strong>: Historical medal counts, country performance, and more.</li>
        <li><strong>Athlete Insights</strong>: Analysis of athlete demographics, age distribution, and performance.</li>
        <li><strong>Medal Prediction</strong>: Machine Learning models to predict medal outcomes based on past data.</li>
    </ul>
    
    <h2>Features</h2>
    <ul>
        <li><strong>Streamlit Dashboard</strong>: A clean and intuitive interface for exploring data and predictions.</li>
        <li><strong>Dynamic Filters</strong>: Interactive filtering by country, year, sport, and athlete.</li>
        <li><strong>Advanced Visualizations</strong>: Charts and graphs powered by Matplotlib, Seaborn, and Plotly.</li>
        <li><strong>Predictive Modeling</strong>: Machine Learning algorithms to analyze and predict outcomes.</li>
    </ul>
    
    <h2>Key Python Libraries Used</h2>
    <ul>
        <li><strong>Data Manipulation and Analysis</strong>: <code>pandas</code>, <code>numpy</code></li>
        <li><strong>Data Visualization</strong>: <code>matplotlib</code>, <code>seaborn</code>, <code>plotly</code>, <code>streamlit</code></li>
        <li><strong>Machine Learning</strong>: <code>scikit-learn</code>, <code>xgboost</code></li>
        <li><strong>Statistical Analysis</strong>: <code>scipy</code>, <code>statsmodels</code></li>
    </ul>
    
    <h2>Machine Learning Algorithms Implemented</h2>
    <ul>
        <li><strong>Linear Regression</strong>: For trend analysis and medal prediction.</li>
        <li><strong>Random Forest</strong>: For classification and feature importance.</li>
        <li><strong>K-Means Clustering</strong>: To group countries or athletes by similar characteristics.</li>
        <li><strong>XGBoost</strong>: To improve predictive accuracy in medal predictions.</li>
        <li><strong>Decision Trees</strong>: For simple and interpretable classification tasks.</li>
    </ul>
    
    <h2>Installation</h2>
    <p>To run the project locally, follow these steps:</p>
    <pre><code>git clone https://github.com/pchhonkar/Olympics-Data-Analysis.git
cd Olympics-Data-Analysis
python3 -m venv myenv
source myenv/bin/activate
pip install -r requirements.txt
streamlit run app.py
</code></pre>
    <p>Open your browser at the provided URL to explore the dashboard.</p>
    
    <h2>Data Source</h2>
    <p>The data used in this project is sourced from publicly available Olympics datasets. Preprocessing steps have been applied to clean and structure the data for analysis and visualization.</p>
    
    <h2>Contributions</h2>
    <p>Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request. If you have suggestions for new features or models, feel free to create an issue.</p>
    
    <h2>License</h2>
    <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>
</body>
</html>
