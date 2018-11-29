# Smooch Public Postman Collection
This repo is a placeholder to the Smooch API Postman Collection.

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/fbbca3a55a8da52c2edf#?env%5BSmooch%20Public%20Env%5D=W3sia2V5IjoidXJsIiwidmFsdWUiOiJodHRwczovL2FwaS5zbW9vY2guaW8iLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6ImFwcElkIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6ImFwcFVzZXJJZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJKV1QiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiYXBwS2V5SWQiLCJ2YWx1ZSI6IiIsImRlc2NyaXB0aW9uIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJpbnRlZ3JhdGlvbklkIiwidmFsdWUiOiIiLCJkZXNjcmlwdGlvbiI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5Ijoic2VydmljZUFjY291bnRJZCIsInZhbHVlIjoiIiwiZGVzY3JpcHRpb24iOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6InNlcnZpY2VLZXlJZCIsInZhbHVlIjoiIiwiZGVzY3JpcHRpb24iOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6InRlbXBsYXRlSWQiLCJ2YWx1ZSI6IiIsImRlc2NyaXB0aW9uIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJ3ZWJob29rSWQiLCJ2YWx1ZSI6IiIsImRlc2NyaXB0aW9uIjoiIiwidHlwZSI6InRleHQiLCJlbmFibGVkIjp0cnVlfV0=)

![Postman Dashboard](/images/postman-dashboard.png "Postman Environment Menu")

Please follow [this guide](https://docs.smooch.io/guide/postman-collection/) to set up your Postman environment


## Environment Variables
| key  | value | Comments |
| :--- | ----- | -------- |
| **url**    | https://api.smooch.io | |
| **appId**  | _id of the app used to send/receive data_ | It can be found in the settings tab your app. |
| **apiVersion**  | _The API version to use. See [API versioning](https://docs.smooch.io/guide/versioning/#api) to learn more._ | |
| **appUserId** | _the user used to send/receive messages_ | This can also be set in the API call params. |
| **JWT**    | _JWT Token_ | See this [guide](https://docs.smooch.io/guide/jwt/#json-web-tokens-jwts) for more information. |

There are many other ways of getting a `JWT` depending on your environment. We provide a few examples in our [guide docs](https://docs.smooch.io/guide/jwt/#json-web-tokens-jwts).
