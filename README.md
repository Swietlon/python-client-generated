# swagger-client
This a simple API

This Python package is automatically generated by the [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) project:

- API version: 1.0.0
- Package version: 1.0.0
- Build package: io.swagger.codegen.v3.generators.python.PythonClientCodegen

## Requirements.

Python 2.7 and 3.4+

## Installation & Usage
### pip install

If the python package is hosted on Github, you can install directly from Github

```sh
pip install git+https://github.com/GIT_USER_ID/GIT_REPO_ID.git
```
(you may need to run `pip` with root permission: `sudo pip install git+https://github.com/GIT_USER_ID/GIT_REPO_ID.git`)

Then import the package:
```python
import swagger_client 
```

### Setuptools

Install via [Setuptools](http://pypi.python.org/pypi/setuptools).

```sh
python setup.py install --user
```
(or `sudo python setup.py install` to install the package for all users)

Then import the package:
```python
import swagger_client
```

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.DefaultApi(swagger_client.ApiClient(configuration))
x = 3.4 # float | First element of sum
y = 3.4 # float | Second element of sum

try:
    api_response = api_instance.addition_get(x, y)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling DefaultApi->addition_get: %s\n" % e)

# create an instance of the API class
api_instance = swagger_client.DefaultApi(swagger_client.ApiClient(configuration))
x = 3.4 # float | The dividend
y = 3.4 # float | The divider

try:
    api_response = api_instance.division_get(x, y)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling DefaultApi->division_get: %s\n" % e)

# create an instance of the API class
api_instance = swagger_client.DefaultApi(swagger_client.ApiClient(configuration))
x = 3.4 # float | First element of product
y = 3.4 # float | Second element of product

try:
    api_response = api_instance.multiplication_get(x, y)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling DefaultApi->multiplication_get: %s\n" % e)

# create an instance of the API class
api_instance = swagger_client.DefaultApi(swagger_client.ApiClient(configuration))
x = 3.4 # float | The minuend
y = 3.4 # float | The subtrahend

try:
    api_response = api_instance.substraction_get(x, y)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling DefaultApi->substraction_get: %s\n" % e)
```

## Documentation for API Endpoints

All URIs are relative to */*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**addition_get**](docs/DefaultApi.md#addition_get) | **GET** /addition | 
*DefaultApi* | [**division_get**](docs/DefaultApi.md#division_get) | **GET** /division | 
*DefaultApi* | [**multiplication_get**](docs/DefaultApi.md#multiplication_get) | **GET** /multiplication | 
*DefaultApi* | [**substraction_get**](docs/DefaultApi.md#substraction_get) | **GET** /substraction | 

## Documentation For Models


## Documentation For Authorization

 All endpoints do not require authorization.


## Author


