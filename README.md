Salary-Prediction
=================

Code for the Adzuna Salary Prediction Kaggle competition - http://www.kaggle.com/c/job-salary-prediction Placed 10th out of approximately 300 teams.

***OVERALL NOTES***


Training needs somewhere between 30 and 60 gigs of RAM and takes between 1 and 3 hours.

We rented an EC2 instance at spot price so training the model should cost around $1.

- A - Os and Hardware -

Os:
Ubuntu 12.10

Hardware:
Amazon EC2 Instance - High-Memory Quadruple Extra Large Instance (m2.4xlarge)

- B - Third Party Software -

Software Used:

Python 2.7x
Scikit Learn
Numpy
Scipy

Installation Commands:

sudo apt-get update
sudo apt-get install build-essential python-dev python-numpy python-setuptools python-scipy libatlas-dev
sudo apt-get remove libatlas3gf-base libatlas-dev
sudo apt-get install libopenblas-dev
sudo apt-get install pip
pip install -U scikit-learn

- C - How To Train Model - 

1) Specify proper paths in SETTINGS.json
2) Run train.py

- D - How To Predict On A New Set -

1) Specify proper paths in SETTINGS.json
2) Run predict.py