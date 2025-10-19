# 🩺 Diabetes Prediction System

This project implements a machine learning model to predict the likelihood of a patient having diabetes based on various diagnostic measurements.

It uses a **Support Vector Machine (SVM) Classifier** trained on the Pima Indians Diabetes Database (provided as `diabetes.csv`) to provide an accurate prediction system.

---

## 🚀 Getting Started

These instructions will get a copy of the project up and running on your local machine.

### Prerequisites

This project is built with **Python 3** and requires several popular data science libraries.

You will need to have **pip** installed to manage the Python packages.

### Installation

1.  **Clone the repository (or download the files):**
    ```bash
    git clone <REPOSITORY_URL>
    ```

2.  **Navigate into the project directory:**
    ```bash
    cd <PROJECT-NAME>
    ```

3.  **Install the required Python libraries:**
    The project relies on `numpy`, `pandas`, and `scikit-learn`.

    ```bash
    pip install numpy pandas scikit-learn
    ```

### Running the System

Ensure that the `diabetes.csv` file is in the same directory as the `diabetes_prediction_system.py` script.

To run the prediction system and see the training and testing accuracy:

```bash
python diabetes_prediction_system.py
