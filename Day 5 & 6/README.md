# To Run Locally

## Dependencies
In order to install all dependencies, run `pip install -r requirements.txt` in your terminal or command prompt. 

## Running
To run the code, open a terminal and navigate to the root directory of this repository. Then, run the following commands:

For MacOS
```bash
export FLASK_ENV=development
export FLASK_APP=app.py
flask run
```

For Windows
```bash
set FLASK_ENV=development
set FLASK_APP=app.py
flask run
```

As import errors arise, you may need to install more modules by using `pip install MODULE_NAME_HERE`.

Finally, once the program runs without errors, navigate to `http://127.0.0.1:5000/` in your browser.
