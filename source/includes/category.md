# Categories

## Get all categories

### HTTP Request

`GET https://api.najotapp.uz/v1/categories`

```bash
curl --request GET \
  --url https://api.najotapp.uz/v1/categories
```

> The above command returns JSON structured like this:

```json
{
  "page": 1,
  "items": [
    {
      "id": 3,
      "image": {
        "id": 11,
        "original_name": "City8",
        "mime_type": "image/jpeg",
        "urls": {
          "original": "https://api.najotapp.uz/cache/images/original/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg",
          "100x_": "https://api.najotapp.uz/cache/images/100x_/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg",
          "300x_": "https://api.najotapp.uz/cache/images/300x_/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg",
          "500x_": "https://api.najotapp.uz/cache/images/500x_/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg"
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
    }
  ],
  "total_count": 1
}
```

## Get single category

### HTTP Request

`GET https://api.najotapp.uz/v1/category/{ID}`

```bash
curl --request GET \
  --url https://api.najotapp.uz/v1/category/{ID}
```

> The above command returns JSON structured like this:

```json
{
  "id": 3,
  "image": {
    "id": 11,
    "original_name": "City8",
    "mime_type": "image/jpeg",
    "urls": {
      "original": "https://api.najotapp.uz/cache/images/original/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg",
      "100x_": "https://api.najotapp.uz/cache/images/100x_/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg",
      "300x_": "https://api.najotapp.uz/cache/images/300x_/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg",
      "500x_": "https://api.najotapp.uz/cache/images/500x_/image/be/d1/4b/bed14bcfb43cd9b94cdbfe1809ae8950610bdbeafe71c5406bac3e91cea155a2.jpg"
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
}
```
