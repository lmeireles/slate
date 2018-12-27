# Authentication

## Login

> JSON success response:

```json
{
    "auth_token": "adee094101e30841XXXXXXXXXXXXXXXX"
}
```

Login user into the platform.

### HTTP Request

`POST <%= @domain %>/account/login`

### Query Parameters

Parameter | Required | Description
--------- | ------- | -----------
receipt | false | The iphone receipt from the store
username | false | The user login (e-mail) identification
partner | false | Provide the partner name to authenticate using the partnerships table
password | true | The password to authenticate
session data parameters | true | reference [here](#session-data)

<aside class="success">
You should provide an <code>username</code> or <code>receipt</code>
</aside>