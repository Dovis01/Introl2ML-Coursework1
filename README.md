# README: Introduction to ML - Decision Tree Coursework (COMP70050)

## Introduction Coursework - (Jupyter Notebook Version)

In this assignment, we will implement a decision tree algorithm and use it to determine one of the indoor locations based on WIFI signal strengths collected from a mobile phone.

Our coursework using Jupyter Notebook. Jupyter Notebook provides an interactive way to develop. Please follow the guide below to properly configure and run.

## Prerequisites

To successfully run the Jupyter Notebooks in this project, make sure your environment has the following tools installed:

1. Python 3.12.3
2. Jupyter Notebook 
3. pip or conda package manager
4. Project dependencies (listed in `requirements.txt`)

## Installation Steps

1. **Clone the Repository**

   Use the following commands to clone this project repository:

   ```
   git clone <repository_url>
   cd <repository_directory>
   ```

2. **Create a Virtual Environment**

   It is recommended to use a virtual environment to avoid dependency conflicts. You can create a virtual environment using conda or venv:

   - Using conda:

     ```
     conda create -n myenv python=3.12.3
     conda activate myenv
     ```

   - Using venv:

     ```
     python -m venv myenv
     source myenv/bin/activate  # On Windows, use `myenv\Scripts\activate`
     ```

3. **Install Dependencies**

   Install all required dependencies for the project using the following command:

   ```
   pip install -r requirements.txt
   ```

4. **Install Jupyter**

   If Jupyter is not already installed, install it using the following command:

   ```
   pip install jupyter
   ```

## Running Jupyter Notebook

1. **Start Jupyter Notebook**

   Run the following command in the project directory to start Jupyter Notebook:

   ```
   jupyter notebook
   ```

   This will start the Jupyter service and open a new tab in your default browser showing a list of notebook files in the project.

2. **Open and Run Notebooks**

   In the Jupyter interface, click on the `.ipynb` file you want to run to open it. Each cell can be run by clicking the "Run" button in the toolbar or using the shortcut `Shift + Enter`.

## Notes

- **Kernel Selection**: Ensure that you are using the kernel that matches your virtual environment. If you cannot select the correct kernel, install `ipykernel` and register the virtual environment using the following command:

  ```
  pip install ipykernel
  python -m ipykernel install --user --name=myenv --display-name "Python (myenv)"
  ```

- **Dependency Changes**: If you add new libraries in the notebook, remember to update the `requirements.txt` file:

  ```
  pip freeze > requirements.txt
  ```

