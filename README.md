# Installation Guide

## 1. Using `conda` *(STRONGLY RECOMMENDED)*

If you are using `conda`, you can create an environment and install dependencies from `requirements.txt`.

### **Step 1: Create a Conda Environment with the right dependencies**
```sh
conda env create -f environment.yml
```

### **Step 2: Activate the Conda Environment**
```sh
conda activate DA_env
```

## 2. Using `pip` and `venv`

If you are using `pip`, it's recommended to create a virtual environment first.

### **Step 1: Create and Activate Virtual Environment**

#### **On macOS/Linux:**
```sh
python3 -m venv my_env
source DA_env/bin/activate
```

#### **On Windows:**
```sh
python -m venv my_env
DA_env\Scripts\activate
```

### **Step 2: Install Dependencies**
Once the virtual environment is activated, install the dependencies:
```sh
pip install -r requirements.txt
```