# 🚦 Federated Traffic Prediction using Federated Learning

A machine learning system that predicts traffic congestion using **Federated Learning**, allowing multiple data sources (cities or sensors) to collaboratively train models **without sharing raw data**.

This approach improves prediction accuracy while **preserving data privacy**.

---

# 📊 Project Overview

Traditional machine learning requires centralized datasets.  
However, traffic data often comes from **multiple distributed sources** such as:

- Smart traffic sensors
- City surveillance systems
- IoT devices
- Transportation departments

Federated Learning enables these systems to **train a shared model collaboratively** while keeping their data local.

---

# ✨ Features

• Traffic congestion prediction using machine learning  
• Privacy-preserving federated training  
• Distributed model training across simulated clients  
• Model aggregation using federated averaging  
• Visualization of training performance  

---

# ⚙️ How Federated Learning Works

1️⃣ Each client (city/node) trains a **local traffic prediction model**

2️⃣ Instead of sending raw traffic data, only **model parameters** are shared

3️⃣ A central server **aggregates the parameters**

4️⃣ The global model is updated

5️⃣ The improved model is redistributed to all clients

---

# 🧠 Machine Learning Model

The project uses:

- **Linear Regression**
- Federated Averaging Algorithm

The model predicts traffic congestion based on traffic flow patterns.

---

# 🛠 Tech Stack

### Programming
- Python

### Machine Learning
- Scikit-Learn
- NumPy
- Pandas

### Federated Learning Concept
- Federated Averaging

---

# 📂 Project Structure
Federated-Traffic-Prediction
│
├ CODE
│ ├ federated_training.py
│ └ client_training.py
│
├ DOCUMENTS
│ ├ abstract.txt
│ └ dataset_reference.txt
│
├ graphs
│ └ federated_training_results.png
│
└ README.md


---

# ▶️ How to Run

### Clone the repository


git clone https://github.com/vennelareddyyy/Federated-Traffic-Prediction.git


### Install dependencies


pip install numpy pandas scikit-learn matplotlib


### Run federated training simulation


python CODE/federated_training.py


---

# 📈 Output

The system generates:

- Global traffic prediction model
- Training performance graphs
- Federated aggregation results

---

# 🚀 Future Improvements

• Integration with **real-time traffic sensor data**  
• Use **Deep Learning (LSTM)** for traffic forecasting  
• Integration with **Smart City IoT networks**  
• Deployment as a **real-time traffic prediction API**

---

# 👩‍💻 Author

**Vennela Reddy**

MS Computer Science – Data Science  
University of North Carolina at Charlotte
