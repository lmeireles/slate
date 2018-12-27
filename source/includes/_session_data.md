# Session data

> JSON example:

```json
  {
    other_request_parameters...,
    "app_id": "com.goread",
    "device_id": "123123123",
    "device_name": "tester",
    "device_type": "smartphone_android",
    "os_version": "andorid"
  }
```

Almost all requests require this parameters so make sure to add them when requested, other case the request will return a 400 error (bad request).

### Parameters

Parameter | Accepts | Description
--------- | ------- | -----------
app_id | string | Application ID
device_id | string | Device unique ID
device_name | string | Device specific name
device_type | "ipad", "tablet_android", "smartphone_android", "iphone" | Device type (from the list)
os_version | string | Device OS system

<aside class="warning">
Remember - Almost all requests require this parameters so make sure to add them when requested!
</aside>