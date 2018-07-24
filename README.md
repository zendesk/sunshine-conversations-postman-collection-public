# Smooch Public Postman Collection
This repo is a placeholder to the Smooch API Postman Collection.

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/e80a5a4ccd17c2a209c9#?env%5BSmooch%20Public%20Env%5D=W3sia2V5IjoidXJsIiwidmFsdWUiOiJodHRwczovL2FwaS5zbW9vY2guaW8iLCJ0eXBlIjoidGV4dCIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiYXBwSWQiLCJ2YWx1ZSI6IiIsInR5cGUiOiJ0ZXh0IiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJ1c2VySWQiLCJ2YWx1ZSI6IiIsInR5cGUiOiJ0ZXh0IiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJKV1QiLCJ2YWx1ZSI6IiIsInR5cGUiOiJ0ZXh0IiwiZW5hYmxlZCI6dHJ1ZX1d)

![Postman Dashboard](/images/postman-dashboard.png "Postman Environment Menu")

Please follow [this guide](https://docs.smooch.io/guide/postman-collection/) to set up your Postman environment


## Environment Variables
| key  | value | Comments |
| :--- | ----- | -------- |
| **url**    | https://api.smooch.io | |
| **appId**  | _id of the app used to send/receive data_ | It can be found in the settings tab your app. |
| **appUserId** | _the user used to send/receive messages_ | This can also be set in the API call params. |
| **JWT**    | _JWT Token_ | See this [guide](https://docs.smooch.io/guide/jwt/#json-web-tokens-jwts) for more information. |

There are many other ways of getting a `JWT` depending on your environment. We provide a few examples in our [guide docs](https://docs.smooch.io/guide/jwt/#json-web-tokens-jwts).
