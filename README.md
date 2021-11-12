# Car Desirability Analysis

### Python based Miniproject implementing KNN and Apriori Algorithm on "Car Evaluation Dataset"

## Languages Used
1. Python (Backend)
2. HTML (Frontend)
3. CSS3 (Frontend)
4. JavaScript (Frontend)

## Frameworks & Libraries Used:
1. Flask
2. Pandas
3. Numpy
4. Arules
5. Scikit-learn

## How to Setup:
1. Clone this repo
2. Open repo folder in Terminal/PS
3. Create virtual-env (Assuming Python3 installed) `python3 -m venv venv`
4. Activate virtual-env (Windows) `.\venv\Scripts\activate` or (Linux) `. venv/bin/activate`
5. Run `pip install -r requirements.txt`
6. Download: [Arules](https://drive.google.com/file/d/1QMkk7B7hfaWkuecpCc0TQIKP7vtfVPtD/view?usp=sharing) and extract into `venv\lib\site-packages\` (replace existing files).
7. Run `python car_evaluation.py`
8. The project will be available at `localhost:5000`

# [Dataset](https://archive.ics.uci.edu/ml/datasets/car+evaluation)

This project implements KKN to predict the Acceptability of a Car having input features based on model trained using the above dataset. It also briefs the factors leading to each of the decisions ( Unacceptable, Acceptable Good `Preferred` & VGood `Optimal` ) using Apriori Algorithm.
