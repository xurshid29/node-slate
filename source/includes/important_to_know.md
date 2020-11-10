# Important To Know

## Get list by category

### HTTP Request

`GET https://api.najotapp.uz/v1/important-to-know?category=cat%202`

```bash
curl --request GET \
  --url 'http://api.najot.test/v1/important-to-know?category=cat%202'
```

> The above command returns JSON structured like this:

```json
{
  "page": 1,
  "items": [
    {
      "id": 26,
      "category": "cat 2",
      "translations": [
        {
          "id": 51,
          "title": "Title 2 RU",
          "body": "Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Cras ultricies ligula sed magna dictum porta. Cras ultricies ligula sed magna dictum porta. Proin eget tortor risus.",
          "locale": "ru"
        },
        {
          "id": 72,
          "title": "Title 2 TG",
          "body": null,
          "locale": "tg"
        },
        {
          "id": 52,
          "title": "Title 2 UZ",
          "body": "Proin eget tortor risus. Sed porttitor lectus nibh. Nulla quis lorem ut libero malesuada feugiat. Curabitur aliquet quam id dui posuere blandit.",
          "locale": "uz"
        }
      ],
      "new_translations": null,
      "current_locale": "ru",
      "default_locale": "ru"
    }
  ],
  "total_count": 1
}
```

## Get single item

### HTTP Request

`GET https://api.najotapp.uz/v1/important-to-know/{ID}`

```bash
curl --request GET \
  --url http://api.najot.test/v1/important-to-know/{ID}
```

> The above command returns JSON structured like this:

```json
{
  "id": 26,
  "category": "cat 2",
  "translations": [
    {
      "id": 51,
      "title": "Title 2 RU",
      "body": "Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Cras ultricies ligula sed magna dictum porta. Cras ultricies ligula sed magna dictum porta. Proin eget tortor risus.",
      "locale": "ru"
    },
    {
      "id": 72,
      "title": "Title 2 TG",
      "body": null,
      "locale": "tg"
    },
    {
      "id": 52,
      "title": "Title 2 UZ",
      "body": "Proin eget tortor risus. Sed porttitor lectus nibh. Nulla quis lorem ut libero malesuada feugiat. Curabitur aliquet quam id dui posuere blandit.",
      "locale": "uz"
    }
  ],
  "new_translations": null,
  "current_locale": "ru",
  "default_locale": "ru"
}
```
