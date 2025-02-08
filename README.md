# Disease Diagnosis by Predictive Health Analysis

## Project Overview
Disease Diagnosis by Predictive Health Analysis is a machine learning-based web application designed to predict diseases based on user input health parameters. The project utilizes a trained model to analyze data and provide diagnostic insights, helping users gain preliminary health assessments.

## Features
- **Machine Learning Model**: Uses a pre-trained model (`model.pkl`) to predict diseases.
- **Web-Based Interface**: Built with Flask, HTML, CSS, and JavaScript for user-friendly interaction.
- **Data Analysis & Model Training**: Jupyter Notebooks are used for data preprocessing and model development.
- **Deployment-Ready**: Configured with a `Procfile` for easy deployment on platforms like Heroku.

## Technologies Used
- **Python** (Flask, Pandas, Scikit-Learn)
- **Jupyter Notebook** (for data analysis & training)
- **HTML, CSS, JavaScript** (for front-end development)
- **Heroku** (for deployment)

## Setup Instructions
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Virtual environment (optional but recommended)
- Pip package manager

### Installation Steps
1. **Clone the repository**
   ```sh
   git clone https://github.com/NightSavage12/Disease-Diagnosis-by-Predictive-Health-Analysis.git
   cd Disease-Diagnosis-by-Predictive-Health-Analysis
   ```

2. **Create and activate a virtual environment (optional)**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```sh
   python app.py
   ```

5. **Access the web application**
   Open your browser and navigate to:
   ```sh
   http://127.0.0.1:5000/
   ```

## Usage Guidelines
- **Enter health parameters** in the web form.
- **Submit the form** to generate a disease prediction.
- **Review the results** and consider consulting a medical professional for further evaluation.

## Deployment
To deploy the application on Heroku:
1. **Login to Heroku**
   ```sh
   heroku login
   ```
2. **Create a new Heroku app**
   ```sh
   heroku create your-app-name
   ```
3. **Deploy the app**
   ```sh
   git push heroku main
   heroku open
   ```

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact
For queries or suggestions, reach out via [GitHub Issues](https://github.com/NightSavage12/Disease-Diagnosis-by-Predictive-Health-Analysis/issues).

