# Important To Know

## Get list by category

### HTTP Request

`GET https://api.najotapp.uz/v1/important-to-know?category=cat%202`

```bash
curl --request GET \
  --url 'http://api.najot.test/v1/important-to-know?category=3'
```

> The above command returns JSON structured like this:

```json
{
  "page": 1,
  "items": [
    {
      "id": 26,
      "category": {
        "id": 3,
        "image": {
          "id": 11,
          "original_name": "City8",
          "mime_type": "image/jpeg",
          "urls": {
            "original": "http://api.najot.test/cache/images/original/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg",
            "100x_": "http://api.najot.test/cache/images/100x_/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg",
            "300x_": "http://api.najot.test/cache/images/300x_/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg",
            "500x_": "http://api.najot.test/cache/images/500x_/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg"
          }
        },
        "translations": [
          {
            "id": 7,
            "title": "Category 1",
            "description": "Category 1",
            "locale": "ru"
          },
          {
            "id": 9,
            "title": "Category 1",
            "description": "Category 1",
            "locale": "tg"
          },
          {
            "id": 8,
            "title": "Category 1",
            "description": "Category 1",
            "locale": "uz"
          }
        ],
        "new_translations": null,
        "current_locale": "ru",
        "default_locale": "ru"
      },
      "translations": [
        {
          "id": 51,
          "title": "Title 2 RU",
          "body": "Body content",
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
          "body": "BODY Content",
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
  "category": {
    "id": 3,
    "image": {
      "id": 11,
      "original_name": "City8",
      "mime_type": "image/jpeg",
      "urls": {
        "original": "http://api.najot.test/cache/images/original/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg",
        "100x_": "http://api.najot.test/cache/images/100x_/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg",
        "300x_": "http://api.najot.test/cache/images/300x_/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg",
        "500x_": "http://api.najot.test/cache/images/500x_/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg"
      }
    },
    "translations": [
      {
        "id": 7,
        "title": "Category 1",
        "description": "Category 1",
        "locale": "ru"
      },
      {
        "id": 9,
        "title": "Category 1",
        "description": "Category 1",
        "locale": "tg"
      },
      {
        "id": 8,
        "title": "Category 1",
        "description": "Category 1",
        "locale": "uz"
      }
    ],
    "new_translations": null,
    "current_locale": "ru",
    "default_locale": "ru"
  },
  "translations": [
    {
      "id": 51,
      "title": "Title 2 RU",
      "body": "Body content",
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
      "body": "BODY Content",
      "locale": "uz"
    }
  ],
  "new_translations": null,
  "current_locale": "ru",
  "default_locale": "ru"
}
```
