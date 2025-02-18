# END-TO-END-DATA-SCIENCE-PROJECT

COMPANY : CODTECH IT SOLUTIONS

NAME : KOMAL BALKRISHNA MOGAL

INTERN ID: CT120FLG

DOMAIN: DATA SCIENCE

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH KUMAR

## **Flask-Based Machine Learning API**  

### **1. Overview**  
- A **machine learning model** is trained and saved for predictions.  
- A **Flask API** is created to handle user requests and return predictions.  
- The API runs **inside Jupyter Notebook** without blocking execution.  

### **2. Key Components**  
- **Model Training**: Dataset is processed, model is trained, evaluated, and saved.  
- **Flask API**:  
  - **`/` Route**: Displays a welcome message.  
  - **`/predict` Route**: Accepts input and returns predictions.  
- **API Execution**: Runs in a **separate thread** for smooth Jupyter Notebook operation.  

### **3. Usage**  
- API runs at **`http://127.0.0.1:5000/`**.  
- Users send a **POST request** with input data.  
- API returns **predictions in JSON format**.  
- Can be tested via **Postman, Python requests, or cURL**.  

### **4. Applications**  
- **AI-Powered Automation** (fraud detection, recommendation systems).  
- **Business Decision-Making** (customer segmentation, forecasting).  
- **Software Integration** (web/mobile app backend, IoT devices).  

### **5. Deployment Considerations**  
- **Local Deployment**: Runs on a personal machine.  
- **Cloud Deployment**: Can be hosted on **AWS, Google Cloud, or Heroku**.  
- **Performance Optimization**: FastAPI, Gunicorn, database integration.  
