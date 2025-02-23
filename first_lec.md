### Steps to Create a Virtual Environment:

#### 1. Navigate to Your Project Directory


#### 2. Create the Virtual Environment:
```
python -m venv <env_name>
```
Example

```
python -m venv API-flask
```

#### 3. Activate the Virtual Environment:
```
.\<env_name>\Scripts\activate
```
Example
```
.\API-flask\Scripts\activate
```

### Steps to Prevent __pycache__ Creation:
```
$env:PYTHONDONTWRITEBYTECODE = "1"
```



#### Steps to perfrom for reactivating the virtual env
```
.\API-flask\Scripts\activate
```

```
$env:FLASK_ENV = "development"
```

```
$env:PYTHONDONTWRITEBYTECODE = "1"
```


- start the server by using the command to turn on the debug mode and to autosave the code changes
```
flask run --debug
```






#### 





























