## Install
virtualenv venv

source venv/bin/activate

pip install -r requirements.txt


## Start app
gunicorn app:app

## Run test
pytest test_zingo.py