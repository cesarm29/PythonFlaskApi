# Flask RESTful API 

This repo shows how to create a simple RESTful API using the Flask web framework. Among the included 

## Install guide


##### Create the virtualenv
```bash
$ mkvirtualenv flask-api-example
```

##### Install dependencies
```bash
$ pip install -r requirements.txt
```

##### Run the app
```bash
$ python run_app.py
```

## Running the app

```bash
# Step 3 requires a DB created
$ sqlite3 library.db < library-schema.sql
$ python run_app.py
```


## Test

```bash
$ make test
```
