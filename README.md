# How to run this project

1. Clone this repository
In your terminal, run the following command:
```bash
git clone https://github.com/Guido-Biotti/Stay-U-nique-Test.git
```
2. Install the virtual environment
```bash
pip install virtualenv
```
3. Create the virtual environment
```bash
virtualenv venv venv
```
4. Run the virtual environment
```bash
# If you are using Git Bash on Windows
source venv/Scripts/activate
# If you are using the terminal on Linux or MacOS
source venv/bin/activate
# If you are using Windows Command Prompt or PowerShell
venv/Scripts/activate
```
5. Install the requirements
```bash
pip install -r requirements.txt
```
6. Run the project using the run button on the left of each cell indiviaduly.
- First run the Scraping.ipynb file to get the data from the website.
- Then run the ETL.ipynb file to clean the data and create the database.
- Finally run the EDA.ipynb file to get the insights from the data.
