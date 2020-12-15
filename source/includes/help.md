# HELP event

## Log help event

### HTTP Request

`POST https://api.najotapp.uz/v1/help`

### Post data

Parameter| Required | Default | Description
--------- | ------- | ------- | -----------
address | Yes | none    | Address object 
deviceId | Yes  | none    | Device ID
helpCenterRequired | Yes  | none    | values - true/false
helpContactsCount | Yes | none    | Sent contacts count
time | Yes | none    | Created time, format - Y/m/d H:i:s
anonymous | Yes | none | Type of the user, values - true/false
accuracy | No | none | Geolocation accuracy
ip | No | none | Client IP address
phoneModel | No | none | Client phone model

```bash
curl --request POST \
  --url http://api.najotapp.uz/v1/help \
  --header 'content-type: application/json' \
  --header 'x-auth-token: qweqweqweqe123123dasd' \
  --data '{
    "address": {
      "administrativeArea": 1,
      "locality": 4,
      "latitude": 46.123123,
      "longitude": 35.345345
    },
    "deviceId": "qweqweqweqe123123dasd",
    "helpCenterRequired": true,
    "helpContactsCount": 3,
    "time": "2020/02/04 13:45:34",
    "anonymous": true,
    "accuracy": "50",
    "ip": "123.12.12.12",
    "phoneModel": "ASasddasd sdf"
  }'
```

<aside class=warning>
This request return an empty response 
</aside>
