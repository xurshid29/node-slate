# News

## Get all news

### HTTP Request

`GET https://api.najotapp.uz/v1/news`

```bash
curl --request GET \
  --url http://api.najot.test/v1/news
```

> The above command returns JSON structured like this:

```json
{
  "page": 1,
  "items": [
    {
      "id": 15,
      "image": {
        "id": 3,
        "original_name": "City6",
        "mime_type": "image/jpeg",
        "urls": {
          "original": "http://api.najot.test/cache/images/original/image/c6/c7/62/c6c762c828ba28faa5ea68789cbdd2b5b776eaa55d772db66041951e9bb26fab.jpg",
          "100x_": "http://api.najot.test/cache/images/100x_/image/c6/c7/62/c6c762c828ba28faa5ea68789cbdd2b5b776eaa55d772db66041951e9bb26fab.jpg",
          "300x_": "http://api.najot.test/cache/images/300x_/image/c6/c7/62/c6c762c828ba28faa5ea68789cbdd2b5b776eaa55d772db66041951e9bb26fab.jpg",
          "500x_": "http://api.najot.test/cache/images/500x_/image/c6/c7/62/c6c762c828ba28faa5ea68789cbdd2b5b776eaa55d772db66041951e9bb26fab.jpg"
        }
      },
      "translations": [
        {
          "id": 43,
          "title": "News 2 RU",
          "body": "Sed porttitor lectus nibh. Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet ligula. Donec sollicitudin molestie malesuada.\r\n\r\nVestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Pellentesque in ipsum id orci porta dapibus. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Curabitur aliquet quam id dui posuere blandit.",
          "locale": "ru"
        },
        {
          "id": 45,
          "title": "News 2 TG",
          "body": "Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Curabitur aliquet quam id dui posuere blandit. Donec rutrum congue leo eget malesuada. Quisque velit nisi, pretium ut lacinia in, elementum id enim.\r\n\r\nCurabitur aliquet quam id dui posuere blandit. Nulla porttitor accumsan tincidunt. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Curabitur aliquet quam id dui posuere blandit.",
          "locale": "tg"
        },
        {
          "id": 44,
          "title": "News 2 UZ",
          "body": "Quisque velit nisi, pretium ut lacinia in, elementum id enim. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Curabitur aliquet quam id dui posuere blandit. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem.\r\n\r\nVivamus suscipit tortor eget felis porttitor volutpat. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet ligula.",
          "locale": "uz"
        }
      ],
      "new_translations": null,
      "current_locale": "ru",
      "default_locale": "ru",
      "created_at": "2020-11-06T04:53:46Z",
      "updated_at": "2020-11-06T04:53:46Z"
    },
    {
      "id": 13,
      "image": {
        "id": 2,
        "original_name": "Colour9",
        "mime_type": "image/png",
        "urls": {
          "original": "http://api.najot.test/cache/images/original/image/c1/dc/ac/c1dcacb9412eeb09d0a0be2097039bc4aad31ab13900037b2170601be19a3cc2.png",
          "100x_": "http://api.najot.test/cache/images/100x_/image/c1/dc/ac/c1dcacb9412eeb09d0a0be2097039bc4aad31ab13900037b2170601be19a3cc2.png",
          "300x_": "http://api.najot.test/cache/images/300x_/image/c1/dc/ac/c1dcacb9412eeb09d0a0be2097039bc4aad31ab13900037b2170601be19a3cc2.png",
          "500x_": "http://api.najot.test/cache/images/500x_/image/c1/dc/ac/c1dcacb9412eeb09d0a0be2097039bc4aad31ab13900037b2170601be19a3cc2.png"
        }
      },
      "translations": [
        {
          "id": 37,
          "title": "Title RU 1",
          "body": "Praesent sapien massa, convallis a pellentesque nec, egestas non nisi. Quisque velit nisi, pretium ut lacinia in, elementum id enim. Proin eget tortor risus. Donec rutrum congue leo eget malesuada.\r\n\r\nQuisque velit nisi, pretium ut lacinia in, elementum id enim. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Proin eget tortor risus. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem.",
          "locale": "ru"
        },
        {
          "id": 39,
          "title": "Title TG 1",
          "body": "Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Curabitur aliquet quam id dui posuere blandit. Nulla quis lorem ut libero malesuada feugiat. Curabitur aliquet quam id dui posuere blandit.\r\n\r\nCurabitur non nulla sit amet nisl tempus convallis quis ac lectus. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Quisque velit nisi, pretium ut lacinia in, elementum id enim. Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui.",
          "locale": "tg"
        },
        {
          "id": 38,
          "title": "Title UZ 1",
          "body": "Praesent sapien massa, convallis a pellentesque nec, egestas non nisi. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Proin eget tortor risus. Quisque velit nisi, pretium ut lacinia in, elementum id enim.\r\n\r\nLorem ipsum dolor sit amet, consectetur adipiscing elit. Cras ultricies ligula sed magna dictum porta. Vivamus suscipit tortor eget felis porttitor volutpat. Nulla quis lorem ut libero malesuada feugiat.",
          "locale": "uz"
        }
      ],
      "new_translations": null,
      "current_locale": "ru",
      "default_locale": "ru",
      "created_at": "2020-11-05T18:19:53Z",
      "updated_at": "2020-11-05T19:25:06Z"
    }
  ],
  "total_count": 2
}
```

## Get single news

### HTTP Request

`GET https://api.najotapp.uz/v1/news/{ID}`

```bash
curl --request GET \
  --url http://api.najot.test/v1/news/{ID}
```

> The above command returns JSON structured like this:

```json
{
  "id": 15,
  "image": {
    "id": 3,
    "original_name": "City6",
    "mime_type": "image/jpeg",
    "urls": {
      "original": "http://api.najot.test/cache/images/original/image/c6/c7/62/c6c762c828ba28faa5ea68789cbdd2b5b776eaa55d772db66041951e9bb26fab.jpg",
      "100x_": "http://api.najot.test/cache/images/100x_/image/c6/c7/62/c6c762c828ba28faa5ea68789cbdd2b5b776eaa55d772db66041951e9bb26fab.jpg",
      "300x_": "http://api.najot.test/cache/images/300x_/image/c6/c7/62/c6c762c828ba28faa5ea68789cbdd2b5b776eaa55d772db66041951e9bb26fab.jpg",
      "500x_": "http://api.najot.test/cache/images/500x_/image/c6/c7/62/c6c762c828ba28faa5ea68789cbdd2b5b776eaa55d772db66041951e9bb26fab.jpg"
    }
  },
  "translations": [
    {
      "id": 43,
      "title": "News 2 RU",
      "body": "Sed porttitor lectus nibh. Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet ligula. Donec sollicitudin molestie malesuada.\r\n\r\nVestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Pellentesque in ipsum id orci porta dapibus. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Curabitur aliquet quam id dui posuere blandit.",
      "locale": "ru"
    },
    {
      "id": 45,
      "title": "News 2 TG",
      "body": "Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Curabitur aliquet quam id dui posuere blandit. Donec rutrum congue leo eget malesuada. Quisque velit nisi, pretium ut lacinia in, elementum id enim.\r\n\r\nCurabitur aliquet quam id dui posuere blandit. Nulla porttitor accumsan tincidunt. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Curabitur aliquet quam id dui posuere blandit.",
      "locale": "tg"
    },
    {
      "id": 44,
      "title": "News 2 UZ",
      "body": "Quisque velit nisi, pretium ut lacinia in, elementum id enim. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Curabitur aliquet quam id dui posuere blandit. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem.\r\n\r\nVivamus suscipit tortor eget felis porttitor volutpat. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet ligula.",
      "locale": "uz"
    }
  ],
  "new_translations": null,
  "current_locale": "ru",
  "default_locale": "ru",
  "created_at": "2020-11-06T04:53:46Z",
  "updated_at": "2020-11-06T04:53:46Z"
}
```
