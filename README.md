 Create a python virtual environment
python3 -m venv ds_env
ds_env\Scripts\Activate

installation of requirements
pip install --upgrade
pip install -r requirements
pip freeze > requirements.txt
python.exe -m pip install --upgrade pip

installation of packages
pip install numpy pandas matplotlib seaborn scikit-learn scipy
pip freeze > requirements.txt