# HELP event

## Log help event

<aside class=warning>
This request requires authentication (X-AUTH-TOKEN header with Device Id)
</aside>

### HTTP Request

`POST https://api.najotapp.uz/v1/help`

### Post data

Parameter | Default | Description
--------- | ------- | -----------
region | none    | Region 
lat  | none    | Latitude
lng  | none    | Longitude
deviceId  | none    | Device ID
helpCenterRequired  | none    | Value can be true, or false
helpContactsCount  | none    | Sent contacts count
time  | none    | Created time

```bash
curl --request POST \
  --url http://api.najotapp.uz/v1/help \
  --header 'content-type: application/json' \
  --header 'x-auth-token: qweqweqweqe123123dasd' \
  --data '{
        "region": "Tashkent",
        "lat": "46.123123",
        "lng": "35.45645",
        "deviceId": "qweqweqweqe123123dasd",
        "helpCenterRequired": true,
        "helpContactsCount": 3,
        "time": "2020/02/04 13:45:34"
      }'
```

<aside class=warning>
This request return an empty response 
</aside>
