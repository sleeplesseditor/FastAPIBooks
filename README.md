# FastAPIBooks

#### Table of Contents
- [Description](#description)
- [Example Screenshots](#example-screenshots)
- [Running the Files Locally](#running-the-files-locally)

## Description
An initial investigation into the use of FastAPI, and the use of CRUD operations 

## Example Screenshots
![Screenshot 2026-09-14 at 11.03.31.png](../../../../Screenshot%202026-09-14%20at%2011.03.31.png)
Example of Swagger displaying initial endpoints for books2.py

## Running the Files Locally
To set up the environments:
- Run `pip install`
- Create a virtual environment by running `python3 -m venv fastapienv`
- Start up the virtual environment with `source fastapienv/bin/activate`

To run `books.py`
- Run `uvicorn books:app --reload`

To run `books2.py`
- Run `uvicorn books2:app --reload`