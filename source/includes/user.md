# User

## Post new user (or update existing by device_id)

### HTTP Request

`POST https://api.najotapp.uz/v1/users`

### Post data

Parameter | Default | Description
--------- | ------- | -----------
name | none | Name of the user
phoneNumber | none | Verified phone number of the user
deviceId | none | Device ID
address | none | Address object

```bash
curl --request POST \
  --url https://api.najotapp.uz/v1/users \
  --header 'content-type: application/json' \
  --data '{
      "name": "Firstname1 Lastname1",
      "phoneNumber": "998998597873",
      "deviceId": "12312313123123",
      "address": {
        "administrativeArea": 1,
        "locality": 4,
        "latitude": 46.123123,
        "longitude": 35.345345
      }
    }'
```

> The above command returns JSON structured like this:

```json
{
  "id": 3,
  "active": true,
  "name": "Test1",
  "gender": null,
  "birth_day": null,
  "phone_number": "998998597873",
  "address": {
    "id": 12,
    "administrativeArea": 1,
    "locality": 4,
    "latitude": 46.123123,
    "longitude": 35.345345
  },
  "verified": true,
  "last_active_time": null,
  "avatar": null,
  "contacts": [],
  "send_my_location": true,
  "notify_nearest_shelter": false,
  "created_at": "2020-11-10T05:12:58Z",
  "updated_at": "2020-11-10T05:12:58Z"
}
```

## Get single user

### HTTP Request

`GET https://api.najotapp.uz/v1/users/{ID}`

```bash
curl --request GET \
  --url http://api.najot.test/v1/users/2
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "active": true,
  "name": "Test1",
  "gender": null,
  "birth_day": null,
  "phone_number": "998998597872",
  "address": {
    "id": 12,
    "administrativeArea": 1,
    "locality": 4,
    "latitude": 46.123123,
    "longitude": 35.345345
  },
  "verified": true,
  "last_active_time": null,
  "avatar": null,
  "contacts": [
    {
      "id": 1,
      "who_is": "Brother 1",
      "phone_number": "998991234567"
    },
    {
      "id": 2,
      "who_is": "Brother 2",
      "phone_number": "998991234568"
    },
    {
      "id": 3,
      "who_is": "Brother 3",
      "phone_number": "998991234569"
    }
  ],
  "send_my_location": true,
  "notify_nearest_shelter": false,
  "created_at": "2020-11-09T19:24:01Z",
  "updated_at": "2020-11-09T19:24:01Z"
}
```

## Full update 

### HTTP Request

`PUT https://api.najotapp.uz/v1/users/{ID}`

### Request data

Parameter | Default | Description
--------- | ------- | -----------
name | none | Name of the user
address | none | Address object

```bash
curl --request PUT \
  --url http://api.najot.test/v1/users/{ID} \
  --header 'content-type: application/json' \
  --data '{
  "name": "Test1",
  "address": {
    "administrativeArea": 1,
    "locality": 3,
    "latitude": 46.123123,
    "longitude": 35.345345
  }
}'
```

> The above command returns JSON structured like this:

```json
{
  "id": 3,
  "active": true,
  "name": "Test1",
  "gender": null,
  "birth_day": null,
  "phone_number": "998998597873",
  "address": {
    "id": 12,
    "administrativeArea": 1,
    "locality": 3,
    "latitude": 46.123123,
    "longitude": 35.345345
  },
  "verified": true,
  "last_active_time": null,
  "avatar": null,
  "contacts": [],
  "send_my_location": true,
  "notify_nearest_shelter": false,
  "created_at": "2020-11-10T05:12:58Z",
  "updated_at": "2020-11-10T05:12:58Z"
}
```

## Partial update 

### HTTP Request

`PATCH https://api.najotapp.uz/v1/users/{ID}`

### Request data

Parameter | Default | Description
--------- | ------- | -----------
name | none | Name of the user
address | none | Address object

```bash
curl --request PATCH \
  --url http://api.najot.test/v1/users/1 \
  --header 'content-type: application/json' \
  --data '{
  "name": "Test1",
  "address": {
    "administrativeArea": 1,
    "locality": 3,
    "latitude": 46.123123,
    "longitude": 35.345345
  }
}'
```

> The above command returns JSON structured like this:

```json
{
  "id": 3,
  "active": true,
  "name": "Test1",
  "gender": null,
  "birth_day": null,
  "phone_number": "998998597873",
  "address": {
    "id": 12,
    "administrativeArea": 1,
    "locality": 3,
    "latitude": 46.123123,
    "longitude": 35.345345
  },
  "verified": true,
  "last_active_time": null,
  "avatar": null,
  "contacts": [],
  "send_my_location": true,
  "notify_nearest_shelter": false,
  "created_at": "2020-11-10T05:12:58Z",
  "updated_at": "2020-11-10T05:12:58Z"
}
```

## Add contact

### HTTP Request

`PATCH https://api.najotapp.uz/v1/users/{ID}`

### Request data

Parameter | Default | Description
--------- | ------- | -----------
contacts | none | array of contacts

```bash
curl --request PATCH \
  --url http://api.najot.test/v1/users/{ID} \
  --header 'content-type: application/json' \
  --data '{
      "contacts": [
        {
          "whoIs": "Brother 1",
          "phoneNumber": "998991234567"
        },
        {
          "whoIs": "Brother 2",
          "phoneNumber": "998991234568"
        },
        {
          "whoIs": "Brother 3",
          "phoneNumber": "998991234569"
        }
      ]
}'
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "active": true,
  "name": "Test1",
  "gender": null,
  "birth_day": null,
  "phone_number": "998998597872",
  "address": {
    "id": 12,
    "administrativeArea": 1,
    "locality": 3,
    "latitude": 46.123123,
    "longitude": 35.345345
  },
  "verified": true,
  "last_active_time": null,
  "avatar": null,
  "contacts": [
    {
      "id": 1,
      "who_is": "Brother 1",
      "phone_number": "998991234567"
    },
    {
      "id": 2,
      "who_is": "Brother 2",
      "phone_number": "998991234568"
    },
    {
      "id": 3,
      "who_is": "Brother 3",
      "phone_number": "998991234569"
    }
  ],
  "send_my_location": true,
  "notify_nearest_shelter": false,
  "created_at": "2020-11-09T19:24:01Z",
  "updated_at": "2020-11-09T19:24:01Z"
}
```


