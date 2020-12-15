# Shelters

## Get all shelters

### HTTP Request

`GET https://api.najotapp.uz/v1/shelters`

```bash
curl --request GET \
  --url http://api.najot.test/v1/shelters?address[administrativeArea]=1
```

> The above command returns JSON structured like this:

```json
{
  "page": 1,
  "items": [
    {
      "id": 2,
      "address": {
        "id": 13,
        "administrativeArea": 1,
        "locality": 1,
        "latitude": 46.123123,
        "longitude": 35.345345
      },
      "phone_number": "998881234567"
    },
    {
      "id": 1,
      "address": {
        "id": 14,
        "administrativeArea": 1,
        "locality": 4,
        "latitude": 46.123123,
        "longitude": 35.345345
      },
      "phone_number": "998991234567"
    }
  ],
  "total_count": 2
}
```

## Get single shelter

### HTTP Request

`GET https://api.najotapp.uz/v1/shelters/{ID}`

```bash
curl --request GET \
  --url http://api.najot.test/v1/shelters/1
```

> The above command returns JSON structured like this:

```json
{
  "id": 1,
  "address": {
    "id": 34,
    "administrativeArea": 1,
    "locality": 4,
    "latitude": 46.123123,
    "longitude": 35.345345
  },
  "phone_number": "998991234567"
}
```
