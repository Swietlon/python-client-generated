# swagger_client.DefaultApi

All URIs are relative to */*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addition_get**](DefaultApi.md#addition_get) | **GET** /addition | 
[**division_get**](DefaultApi.md#division_get) | **GET** /division | 
[**multiplication_get**](DefaultApi.md#multiplication_get) | **GET** /multiplication | 
[**substraction_get**](DefaultApi.md#substraction_get) | **GET** /substraction | 

# **addition_get**
> float addition_get(x, y)



Returns sum of x and y

### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.DefaultApi()
x = 3.4 # float | First element of sum
y = 3.4 # float | Second element of sum

try:
    api_response = api_instance.addition_get(x, y)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling DefaultApi->addition_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **x** | **float**| First element of sum | 
 **y** | **float**| Second element of sum | 

### Return type

**float**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **division_get**
> float division_get(x, y)



Returns quotient of x and y

### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.DefaultApi()
x = 3.4 # float | The dividend
y = 3.4 # float | The divider

try:
    api_response = api_instance.division_get(x, y)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling DefaultApi->division_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **x** | **float**| The dividend | 
 **y** | **float**| The divider | 

### Return type

**float**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **multiplication_get**
> float multiplication_get(x, y)



Returns product of x and y

### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.DefaultApi()
x = 3.4 # float | First element of product
y = 3.4 # float | Second element of product

try:
    api_response = api_instance.multiplication_get(x, y)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling DefaultApi->multiplication_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **x** | **float**| First element of product | 
 **y** | **float**| Second element of product | 

### Return type

**float**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **substraction_get**
> float substraction_get(x, y)



Returns the difference x and y

### Example
```python
from __future__ import print_function
import time
import swagger_client
from swagger_client.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = swagger_client.DefaultApi()
x = 3.4 # float | The minuend
y = 3.4 # float | The subtrahend

try:
    api_response = api_instance.substraction_get(x, y)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling DefaultApi->substraction_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **x** | **float**| The minuend | 
 **y** | **float**| The subtrahend | 

### Return type

**float**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

