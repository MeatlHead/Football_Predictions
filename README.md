# Football_Predictions
This project demonstrates how to create a Flask web application that integrates with the SmartBets API to predict future football matches. 
The code includes error handling for API interactions and unit tests to ensure robustness.
The user interface is designed to display prediction results and error messages clearly using Bootstrap for styling. 

# Instructions for Installing and Running the Project
## Clone the Repository:
git clone https://github.com/MeatlHead/Football_Predictions.git
cd flask_smartbets

## Set Up Virtual Environment:

python3 -m venv venv
source venv/bin/activate 

# On Windows use 
venv\Scripts\activate

## Install Dependencies:
pip install -r requirements.txt

## Set Up Environment Variables:

Create a .env file in the root directory and add your SmartBets API key:

SMARTBETS_API_KEY=your_api_key

# Run the Application:
python run.py

# Run Unit Tests:
python -m unittest discover tests
