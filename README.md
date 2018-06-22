# Smooch Public Postman Collection

---
## Table of Contents
This collection currently contains the following APIs (⭐ the repo! We're always adding more sections.)
### Core
- [App User](https://docs.smooch.io/rest/#app-user)
- [Conversation](https://docs.smooch.io/rest/#schema)
- [Message Types](https://docs.smooch.io/rest/#message-types)
---
## Setup

### Get the Collection
There are two ways you can use the Smooch Postman Collection
1. Fork or clone this repo and import the `Smooch.postman_collection.json` file into your Postman Workspace.
2. _get it from `url` --public postman collection published on the web_

### Setup Global Variables
To use this collection, you will need to have a [Smooch account](https://smooch.io), and have at least one app setup. You will need the following values to run most of the API calls in the collection: `appId`, `userId`, `JWT`, and `messageId`.
1. `appId`: The ID of the app with which you want to test the API.
2. `userId`: The user to whom you want to send the test messages. (If you plan on sending to different users, you can set the `userId` value on a per call basis in the parameters instead). _see below_
3. `JWT`: You will need a json web token to authenticate your calls.

**Note:** _`messageId` is only needed for the `DELETE Message` API call_

|    action     |  screenshot  |
| ------------- | ------------ |
| 1. Set environment to `Smooch`. | ![alt text](/images/environment.png "Postman Environment Menu") |
| 2. Open Settings | ![alt text](/images/environment.1.png "Postman Environment Settings Button") |
| 3. Add your values here | ![alt text](/images/global-variables.png "Postman Environment Variables") |

### Get a JWT
The easiest way to get one is to visit [https://jwt.io/](https://jwt.io/) and provide the following values:

![alt text](/images/jwt-io-sample.png "Postman Environment Menu")

> :warning: Don't forget to add the **SECRET** that is paired with this **KEY_ID**.
>
> ![alt text](/images/smooch-account-settings.png "Smooch Account settings")

There are many other ways of getting a `JWT` depending on your environment. We provide a few examples in our [guide docs](https://docs.smooch.io/guide/jwt/#json-web-tokens-jwts).
