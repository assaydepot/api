# Welcome to Assay Depot's JSON API Documentation
Assay Depot's JSON API gives read-only access to vendors and services. To use the API you must have a developer authentication token. During the pre-release period, please contact cpetersen@assaydepot.com to obtain a token.

## Location
The API is accessible at `/api` on whatever website you use. For instance, public marketplace customers (users of http://www.assaydepot.com) can access the api at:
```
https://www.assaydepot.com/api
```
Vendors can access the api at:
```
https://backoffice.assaydepot.com/api
```
And private RX customers can access the api using their custom url:
```
https://[custom].assaydepot.com/api
```

## Authentication
The API requires the user to authenticate. For convenience you may authenticate using a token associated with your account. During the pre-release period, please contact cpetersen@assaydepot.com to obtain a token.

You can specify the authentication token on the query string using the `auth_token` query parameter. For instance:
```
https://www.assaydepot.com/api?auth_token=1234567890
```

The authentication token is only strictly required for the first request of the session, but you may include it with every request.

## Vendors
