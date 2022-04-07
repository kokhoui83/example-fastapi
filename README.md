# Example FastAPI

## Requirements
- pipenv
- python 3.x

## Setup
- setup virtual environment
```
pipenv --python 3.9
```
- install dependencies
```
pipenv install
```

## Run
- start server
```
# method 1
uvicorn main:app --reload

# method 2
python server.py
```
- call api
```
➜  ~ curl localhost:8000 | jq
^[[5~  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    17  100    17    0     0   8500      0 --:--:-- --:--:-- --:--:--  8500
{
  "Hello": "World"
}
```
- api documentations http://localhost:8000/docs