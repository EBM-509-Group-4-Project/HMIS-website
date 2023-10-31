# HMIS-website

## How to run the Django-website locally

1. Install [python](https://www.python.org/downloads/) and [venv](https://docs.python.org/3/library/venv.html) a virtual environment using pip.
2. Create a virtual environment using `python -m venv env`
3. Once you have created the virtual environment, activate it using `source env/bin/activate` on Linux or `env\Scripts\activate.bat` on Windows.
4. Get the project by cloning the repository or downloading the zip file. Then, navigate to the project directory and install the requirements using `pip install -r requirements.txt`
5. Once the requirements are installed, make migrations using `python manage.py makemigrations` and then migrate using `python manage.py migrate`
6. Finally, run the server using `python manage.py runserver` and navigate to the url shown in the terminal.
7. Or, enter the following URL in your browser: `http://127.0.0.1:8000/`
8. To deactivate the virtual environment, use `deactivate` on Linux or `env\Scripts\deactivate.bat` on Windows.


   # references
   - https://github.com/sumitkumar1503/hospitalmanagement
