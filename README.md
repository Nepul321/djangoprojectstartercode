# djangoprojectstartercode

### Starter code for any Django project

Clone this repo ``` git clone https://github.com/Nepul321/djangoprojectstartercode.git  ```

In your terminal enter ``` cd djangoprojectstartercode  ```

Create a virtual environment using ``` python -m venv <nameofyourvirtualenv>``` (If you are on mac the command will be ``` python3 -m venv <nameofyourvirtualenv> ```)

Activate the virtual environment. ( ``` source <nameofyourvirtualenv>/bin/activate``` on mac or linux and ``` ./<nameofyourvirtualenv>/Scripts/activate ``` on windows)

Then enter  ``` pip install -r requirements.txt ``` in your terminal.

After that enter ``` python manage.py migrate ```.

And finally ``` python manage.py runserver  ```

Then go to http://localhost:8000/ or http://127.0.0.1:8000/ and you will see a basic "Hello World" app.
