# Flask Test Application

## Introduction

## Running the Application

1. Clone the repository, then open your python terminal

2. _(optional)_ Setup your virtual ENV

3. Install the dependencies

  ```
  pip install -r requirements.txt
  ```

4. _(on Windows)_ Run the Web Server

  ```
  waitress-serve --listen=*:8000 wsgi:app
  ```

4. _(on Linux/Mac)_ Run the Web Server

  ```
  gunicorn --bind 0.0.0.0:8000 wsgi:app
  ```
