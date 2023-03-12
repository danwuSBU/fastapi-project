# fastapi-project (WORK IN PROGRESS DON'T JUDGE)

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

## UI

`cd` to `/fastapi-project/ui`

Make sure you have the API running locally (see above) and yarn installed (`npm install --global yarn`).

### Install dependencies

`/fastapi-project/ui$ yarn install`

### Generate client

`/fastapi-project/ui$ yarn run generate-client` (you will need to run this every time you edit the API).

## Run the app

`/fastapi-project/app$ uvicorn main:app --reload` and `/fastapi-project/ui$ yarn start` in two terminals.
