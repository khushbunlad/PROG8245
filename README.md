# PROG8245
Machine Learning Programming

### Project and environment setup

1. Move to project directory "PROG8431" where you have cloned the project
2. Create virtual environment with name **"venvPROG8245"**
    - Make sure ```python --version``` is set to **12.3.6** in your system
    - ```python -m venv venvPROG8245```
3. Activate environment
    - ```.\venvPROG8245\Scripts\Activate.ps1```
    - In case you are using visual studio code, Choose the environment from menu as active environment
4. Install packages mentioned in **"requirements.txt"**
    - ```pip install -r requirements.txt```
5. Select **"venvPROG8245"** environment in your IDE
6. Create folder named **"Dataset"** in your project directory
7. Move all files downloaded from Kaggle dataset in the "Dataset" Directory
8. Open "Workshop1.ipynb" and run first program snippet. 
9. It should display top 5 rows from file "RAW_recipe.csv"


### Update Requirements.txt file once installing new packages

```pip freeze > requirements.txt```