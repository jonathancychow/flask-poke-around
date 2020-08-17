This repo is based on the Miguel's tutorial from this [link.](https://play.google.com/store/apps/details?id=com.pas.webcam&hl=en_GB) 

## Python Library Installation 
- Run the command prompt with admin privilege and install the Python package Poetry as follow: 
```bash
pip install poetry
```
- Restart the command prompt and cd to the repo directory 
- Install the required libraries by invoking poetry 
```bash
poetry install 
``` 

## Token 
Get token from the service
```bash
http --auth <username>:<password> POST http://localhost:5000/api/tokens
``` 

Get request with the token
``` 
http GET http://localhost:5000/api/users/3 "Authorization
:Bearer somerandomwordsgohere"
``` 