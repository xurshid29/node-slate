# Shelters

## Get all shelters

### HTTP Request

`GET https://api.najotapp.uz/v1/shelters`

```bash
curl --request GET \
  --url http://api.najot.test/v1/shelters
```

> The above command returns JSON structured like this:

```json
{
  "page": 1,
  "items": [
    {
      "id": 2,
      "administrative_area": "Bukhara",
      "locality": "Bukhara",
      "address_line": "Some street, 45",
      "phone_number": "998881234567",
      "latitude": "34.123123",
      "longitude": "45.123231"
    },
    {
      "id": 1,
      "administrative_area": "Samarkand",
      "locality": "Jomboy",
      "address_line": "Some street, 23",
      "phone_number": "998991234567",
      "latitude": "34.123123",
      "longitude": "45.123231"
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
  "administrative_area": "Samarkand",
  "locality": "Jomboy",
  "address_line": "Some street, 23",
  "phone_number": "998991234567",
  "latitude": "34.123123",
  "longitude": "45.123231"
}
```
