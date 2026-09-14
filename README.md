# FastAPIBooks

#### Table of Contents
- [Description](#description)
- [Example Screenshots](#example-screenshots)
- [Running the Files Locally](#running-the-files-locally)

## Description
An initial investigation into the use of FastAPI, and the use of CRUD operations, as part of coursework for [Eric Roby's Udemy course](https://www.udemy.com/course/fastapi-the-complete-course). 

## Example Screenshots
<img width="1919" height="841" alt="Screenshot 2026-09-14 at 11 03 31" src="https://github.com/user-attachments/assets/68ca7597-ad75-4ef7-845d-f7e071edcea5" />
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
