# fastapi-project

## Setup

`cd` to project root `/fastapi-project`

### Create the virtual environment

`/fastapi-project$ sudo apt install python3.9-venv`

`/fastapi-project$ python3.9 -m venv .venv`

### Activate the virtual environment

`/fastapi-project$ source .venv/bin/activate`

### Install requirements

`/fastapi-project$ pip install -r requirements.txt`

## API

`cd` to `/fastapi-project/app`

### Run the API locally

`/fastapi-project/app$ uvicorn main:app --reload`

Open Swagger in browser: `http://127.0.0.1:8000/docs#/`
