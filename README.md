# python-firebase-crud
Experimenting CRUD operations to firebase realtime DB with python

# Assumptions: 
* Firebase data-store has structure like `/<collection-name>/<key>/<data>`
* Data can be fetched via a URL GET
* We will implement READ, UPDATE and DELETE (UPDATE will be UPSERT)
* Script will have a config and a key section that need be updated by the user


# Package requirements:
In a new python3 virtualenv:
  * requests
  * pyrebase
  * google-auth-oauthlib
  * pyasn1-modules


# Basic tutorial: 
https://github.com/thisbejim/Pyrebase


# Script signature:
```
$firebase_crud.py --collection <string> --key <string> --action get
$firebase_crud.py --collection <string> --key <string> --action set --url <url-string>
$firebase_crud.py --collection <string> --key <string> --action delete
```
