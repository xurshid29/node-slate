# Inspectors

## Get all inspectors

### HTTP Request

`GET https://api.najotapp.uz/v1/inspectors`

```bash
curl --request GET \
  --url https://api.najotapp.uz/v1/inspectors?address[administrativeArea]=1
```

> The above command returns JSON structured like this:

```json
{
  "page": 1,
  "items": [
    {
      "id": 857,
      "first_name": "Севара",
      "last_name": "Садуллаева",
      "middle_name": "Абдулакимовна",
      "mobile_phone_number": "998991231231",
      "work_phone_number": "998711231231",
      "rank": "Подполковник",
      "position": "ИИБ ҲПБ Хотин-қизлар масалалари бўйича катта инспектор",
      "address": {
        "id": 542,
        "administrative_area": 1,
        "locality": 1,
        "address_line": "Яшнобод тумани 7-сон ИИБ ҲПБ Хотин-қизлар масалалари бўйича катта инспектор",
        "latitude": null,
        "longitude": null
      },
      "created_at": "2020-12-06T11:06:21Z",
      "updated_at": "2020-12-09T17:38:56Z"
    }
  ],
  "total_count": 1
}
```

## Get single inspector

### HTTP Request

`GET https://api.najotapp.uz/v1/inspectors/{ID}`

```bash
curl --request GET \
  --url http://api.najot.test/v1/inspectors/857
```

> The above command returns JSON structured like this:

```json
{
  "id": 857,
  "first_name": "Севара",
  "last_name": "Садуллаева",
  "middle_name": "Абдулакимовна",
  "mobile_phone_number": "998991231231",
  "work_phone_number": "998711231231",
  "rank": "Подполковник",
  "position": "ИИБ ҲПБ Хотин-қизлар масалалари бўйича катта инспектор",
  "address": {
    "id": 542,
    "administrative_area": 1,
    "locality": 1,
    "address_line": "Яшнобод тумани 7-сон ИИБ ҲПБ Хотин-қизлар масалалари бўйича катта инспектор",
    "latitude": null,
    "longitude": null
  },
  "created_at": "2020-12-06T11:06:21Z",
  "updated_at": "2020-12-09T17:38:56Z"
}
```
