# Python & Machine Learning Portfolio

Practical ML projects covering deep learning, data pipelines, and full-stack application development.

## Projects

### 1. MNIST Digit Recognition — CNN

Convolutional Neural Network trained on the MNIST dataset for handwritten digit classification.

| Component | Details |
|-----------|---------|
| Model | CNN with Conv2D, MaxPooling, Dense layers |
| Training | MNIST dataset (60K train / 10K test images) |
| Output | Saved model (`bestmodel.h5`) for inference |
| App | Interactive prediction app (`app.py`) — upload an image and get the predicted digit |

**Tech:** `Python` `TensorFlow/Keras` `NumPy` `OpenCV`

**Files:** `MNIST.ipynb` · `bestmodel.h5` · `app.py`

---

### 2. Railway Management System

Full-stack database application for managing railway operations — booking, scheduling, and passenger records.

| Component | Details |
|-----------|---------|
| Backend | Python application with SQL database integration |
| Database | MySQL — tables for trains, passengers, bookings, schedules |
| Features | Ticket booking, seat availability, train search, passenger management |

**Tech:** `Python` `MySQL` `SQL`

**Files:** `main.py` · `main_sql_file.sql`

---

## How to Run

```bash
# MNIST Digit Recognition
pip install tensorflow numpy opencv-python
jupyter notebook MNIST.ipynb
python app.py

# Railway Management System
# Import the database schema
mysql -u root -p < main_sql_file.sql
python main.py
```

## Tech Stack

`Python` `TensorFlow` `Keras` `OpenCV` `NumPy` `Pandas` `MySQL` `Jupyter`
