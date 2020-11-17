# Logging

## Log event

### HTTP Request

`POST https://api.najotapp.uz/v1/log`

### Post data

Parameter | Default | Description
--------- | ------- | -----------
operation | none    | Value can be one of these choices: help, important to know, testing, news 
deviceId  | none    | Device ID
resourceId  | none    | (Optional) Resource ID
lat  | none    | (Optional) Latitude
lng  | none    | (Optional) Longitude

```bash
curl --request POST \
  --url http://api.najotapp.uz/v1/log \
  --header 'content-type: application/json' \
  --data '{
      "operation": "help",
      "deviceId": "234242424234234",
      "lat": 46.234234,
      "lng": 36.4345534
    }'
```
