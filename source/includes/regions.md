# Regions

## Get administrative areas

### HTTP Request

`GET https://api.najotapp.uz/v1/administrative-areas`

```bash
curl --request GET \
  --url https://api.najotapp.uz/v1/administrative-areas
```

> The above command returns JSON structured like this:

```json
{
  "page": 1,
  "items": [
    {
      "id": 12,
      "translations": [
        {
          "id": 34,
          "name": "Navoiy viloyati",
          "locale": "ru"
        },
        {
          "id": 36,
          "name": "Navoiy viloyati",
          "locale": "tg"
        },
        {
          "id": 35,
          "name": "Navoiy viloyati",
          "locale": "uz"
        }
      ],
      "new_translations": null,
      "current_locale": "ru",
      "default_locale": "ru"
    },
    {
      "id": 13,
      "translations": [
        {
          "id": 37,
          "name": "Xorazm viloyati",
          "locale": "ru"
        },
        {
          "id": 39,
          "name": "Xorazm viloyati",
          "locale": "tg"
        },
        {
          "id": 38,
          "name": "Xorazm viloyati",
          "locale": "uz"
        }
      ],
      "new_translations": null,
      "current_locale": "ru",
      "default_locale": "ru"
    },
    {
      "id": 14,
      "translations": [
        {
          "id": 40,
          "name": "Qoraqalpog'iston Respublikasi",
          "locale": "ru"
        },
        {
          "id": 42,
          "name": "Qoraqalpog'iston Respublikasi",
          "locale": "tg"
        },
        {
          "id": 41,
          "name": "Qoraqalpog'iston Respublikasi",
          "locale": "uz"
        }
      ],
      "new_translations": null,
      "current_locale": "ru",
      "default_locale": "ru"
    }
  ],
  "total_count": 14
}
```


## Get localities by administrative area

### HTTP Request

`GET https://api.najotapp.uz/v1/administrative-areas/{ID}/localities`

```bash
curl --request GET \
  --url https://api.najotapp.uz/v1/administrative-areas/1/localities
```

> The above command returns JSON structured like this:

```json
{
  "page": 1,
  "items": [
    {
      "id": 1,
      "translations": [
        {
          "id": 1,
          "name": "Uchtepa tumani",
          "locale": "ru"
        },
        {
          "id": 2,
          "name": "Uchtepa tumani",
          "locale": "uz"
        },
        {
          "id": 3,
          "name": "Uchtepa tumani",
          "locale": "tg"
        }
      ],
      "new_translations": null,
      "current_locale": "ru",
      "default_locale": "ru"
    },
    {
      "id": 2,
      "translations": [
        {
          "id": 4,
          "name": "Mirzo ulug‘bek tumani",
          "locale": "ru"
        },
        {
          "id": 5,
          "name": "Mirzo ulug‘bek tumani",
          "locale": "uz"
        },
        {
          "id": 6,
          "name": "Mirzo ulug‘bek tumani",
          "locale": "tg"
        }
      ],
      "new_translations": null,
      "current_locale": "ru",
      "default_locale": "ru"
    }
  ],
  "total_count": 11
}
```
