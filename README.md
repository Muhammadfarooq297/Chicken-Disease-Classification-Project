# Chicken Coccidiosis Classification

## **Image Classification of Chicken Fecal Samples**  

---

## 🎯 Problem Statement  
The goal of this project was to develop an image classification model to **detect coccidiosis in chickens** based on fecal images. Coccidiosis is a significant health issue in poultry farming, and early detection can help reduce mortality rates by enabling timely intervention.

---

## 🚀 Key Contributions

### 🔍 Data Collection and Preprocessing
- Collected a dataset of chicken fecal images categorized into **healthy** and **unhealthy** samples. 📷

### 🔧 Transfer Learning & Model Development
- Leveraged **VGG16**, a pretrained model on the ImageNet dataset, to build the classification model. 
- Implemented custom layers on top of the VGG16 architecture to adapt it specifically for the chicken fecal image classification task. 🔄

### 🤖 Model Training and Evaluation
- Trained the model using the prepared dataset, applying techniques like **cross-validation** and **hyperparameter tuning** to improve performance. 📈
- Evaluated the model using metrics such as **accuracy**, **precision**, and **recall** to ensure reliable predictions. ✔️

### 🌐 Web Application for Real-Time Predictions
- Developed a **Flask web application** that allows users to upload fecal images and receive predictions on whether the chicken is healthy or affected by coccidiosis. 🌍

### ☁️ Cloud Deployment
- **Deployment on AWS & Azure:** The model and web app can be deployed to cloud platforms for scalability and accessibility. Instructions will be provided for both AWS and Azure deployments. ☁️🚀

### 🧹 Clean Code and Modular Programming
- Followed best practices in coding to ensure **modular**, **clean**, and **extensible** code, promoting maintainability and collaboration. 🧑‍💻📦

---

## 🛠️ Technologies Used

- **Programming Languages:** Python 🐍
- **Data Analysis & Visualization:** `Pandas`, `NumPy`, `Matplotlib`
- **Machine Learning & Deep Learning:** `Keras`, `TensorFlow`, VGG16
- **Web Frameworks:** `Flask`
- **Cloud Platforms:** AWS ☁️, Azure ☁️
- **Version Control:** `Git`, `GitHub`
- **Development Practices:** Modular Programming, Clean Code (PEP8)

---

## 📝 How to Run the Project

1. **Clone the repository:**  
    ```bash
    git clone https://github.com/Muhammadfarooq297/Chicken-Disease-Classification-Project.git
    ```

2. **Navigate to the project directory:**  
    ```bash
    cd chicken-coccidiosis-classification
    ```

3. **Install the required dependencies:**  
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask web application:**  
    ```bash
    python app.py
    ```

5. **Access the web application at:**  
    `http://localhost:5000/`

---

## 📁 Project Structure

The project is organized into the following structure:

- **cnnClassifier/**
  - **.github/**
    - **workflows/**
      - `.gitkeep`
  - **src/**
    - **cnnClassifier/**
      - `__init__.py`
      - **components/**
        - `__init__.py`
      - **utils/**
        - `__init__.py`
      - **config/**
        - `__init__.py`
        - `configuration.py`
      - **pipeline/**
        - `__init__.py`
      - **entity/**
        - `__init__.py`
      - **constants/**
        - `__init__.py`
  - **config/**
    - `config.yaml`
  - `dvc.yaml`
  - `params.yaml`
  - `requirements.txt`
  - `setup.py`
  - **research/**
    - `trials.ipynb`
  - **templates/**
    - `index.html`

## Workflows

1. Update `config.yaml`
2. Update `secrets.yaml` [Optional]
3. Update `params.yaml`
4. Update the entity
5. Update the configuration manager in `src/config`
6. Update the components
7. Update the pipeline 
8. Update `main.py`
9. Update the `dvc.yaml`

🎉 Feel free to explore the code and contribute to improvements!
