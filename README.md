
# Fake Profile Detection System

## Project Overview

The **Fake Profile Detection System** is a Machine Learning based web application that predicts whether a social media account is **real or fake** based on profile information.
The system uses a trained machine learning model and an interactive web interface built with Streamlit.

Users can enter profile details such as profile picture availability, description length, number of posts, followers, and following count.
The model analyzes these inputs and predicts whether the profile is **Fake** or **Real**.

---

## Tech Stack

* Python
* NumPy
* Scikit-learn
* Streamlit
* Pickle

---

## Features

* Interactive web interface
* Machine learning based prediction
* Simple and clean UI
* Real-time prediction
* Background styled interface

---

## Input Features Used

The model makes predictions using the following profile attributes:

1. Profile Picture (Yes / No)
2. Description Length
3. Number of Posts
4. Followers Count
5. Following Count

---

## Project Structure

```
fake-profile-detection/
│
├── app.py
├── fake_profile_model.pkl
├── matrix code.jpg
├── requirements.txt
└── README.md
```

---

## Installation

### 1. Clone the repository

```
git clone https://github.com/your-username/fake-profile-detection.git
```

### 2. Navigate to project folder

```
cd fake-profile-detection
```

### 3. Install required libraries

```
pip install -r requirements.txt
```

---

## Run the Application

```
streamlit run app.py
```

After running the command, the application will open automatically in your browser.

---

## How It Works

1. User enters profile details in the web interface.
2. Inputs are converted into numerical features.
3. The trained machine learning model processes the features.
4. The system predicts whether the profile is **Fake** or **Real**.

---

## Future Improvements

* Use larger datasets for better accuracy
* Add more profile features
* Deploy the app online
* Improve UI design

---

## Author

Developed as a Machine Learning project for learning and portfolio purposes.


# Output

## for real : 
<img width="1894" height="908" alt="Image" src="https://github.com/user-attachments/assets/7ac601e5-b78a-42ea-9bdf-17f87d79bfe9" />

##for fake: 
<img width="1600" height="702" alt="Image" src="https://github.com/user-attachments/assets/6db94d45-bab2-4a1b-9e11-47e464648fa6" />
