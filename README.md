# my-first-app

#Setup
Create and activate a virtual environment:

```sh

conda create -n my-first-env python=3.10

conda activate my-first-env
```

Install packages:
```sh 
pip install -r requirements.txt 
```



Obtain an [API Key from Alphavantage](https://www.alphavantage.co/support/#api-key) or from the prof (`ALPHAVANTAGE_API_KEY`).


Create a ".env" file and paste in the following contents 
```sh
#this is the .env file...
Obtain an API key from Sendgrid: you must first follow the setup instructions to create an account, verify your account, setup a single sender, and obtain an API Key.


ALPHAVANTAGE_API_KEY = "______"

SENDGRID_API_KEY = getpass("Please input your Sendgrid API Key: ")
SENDER_ADDRESS = getpass("Please input your Sender Email Address: ")

```

## Usage
Run the example script:

```sh
python app/my_script.py
```


Run the unemployment report 
```sh
python -m app.unemployment
```

send an email:

```sh
python app/email_service.py
```

#Testing

Run tests:

```sh
pytest
```
