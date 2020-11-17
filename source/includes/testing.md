# Testing

## Get testing list

### HTTP Request

`GET https://api.najotapp.uz/v1/testings`

```bash
curl --request GET \
  --url http://api.najotapp.uz/v1/testings
```

> The above command returns JSON structured like this:

```json
{
  "page": 1,
  "items": [
    {
      "id": 60,
      "questions": [
        {
          "id": 104,
          "choices": [
            {
              "translations": {
                "ru": {
                  "name": "Choice 1"
                },
                "uz": {
                  "name": "Choice 1"
                },
                "tg": {
                  "name": "Choice 1"
                }
              },
              "weight": 10
            },
            {
              "translations": {
                "ru": {
                  "name": "Choice 2"
                },
                "uz": {
                  "name": "Choice 2"
                },
                "tg": {
                  "name": "Choice 2"
                }
              },
              "weight": 30
            }
          ],
          "translations": [
            {
              "id": 310,
              "question": "Question 1",
              "locale": "ru"
            },
            {
              "id": 312,
              "question": "Question 1",
              "locale": "tg"
            },
            {
              "id": 311,
              "question": "Question 1",
              "locale": "uz"
            }
          ],
          "new_translations": null,
          "current_locale": "ru",
          "default_locale": "ru"
        },
        {
          "id": 106,
          "choices": [
            {
              "translations": {
                "ru": {
                  "name": "Choice 1"
                },
                "uz": {
                  "name": "Choice 1"
                },
                "tg": {
                  "name": "Choice 1"
                }
              },
              "weight": 20
            },
            {
              "translations": {
                "ru": {
                  "name": "Choice 2"
                },
                "uz": {
                  "name": "Choice 2"
                },
                "tg": {
                  "name": "Choice 2"
                }
              },
              "weight": 30
            }
          ],
          "translations": [
            {
              "id": 316,
              "question": "Question 2",
              "locale": "ru"
            },
            {
              "id": 318,
              "question": "Question 2",
              "locale": "tg"
            },
            {
              "id": 317,
              "question": "Question 2",
              "locale": "uz"
            }
          ],
          "new_translations": null,
          "current_locale": "ru",
          "default_locale": "ru"
        }
      ],
      "results": [
        {
          "interval": {
            "min": 0,
            "max": 40
          },
          "translations": {
            "ru": {
              "title": "Title 1",
              "description": "Desc 1"
            },
            "uz": {
              "title": "Title 1",
              "description": "Desc 1"
            },
            "tg": {
              "title": "Title 1",
              "description": "Desc 1"
            }
          }
        },
        {
          "interval": {
            "min": 40,
            "max": 70
          },
          "translations": {
            "ru": {
              "title": "Title 2",
              "description": "Desc 2"
            },
            "uz": {
              "title": "Title 2",
              "description": "Desc 2"
            },
            "tg": {
              "title": "Title 2",
              "description": "Desc 2"
            }
          }
        }
      ],
      "image": {
        "id": 10,
        "original_name": "Colour6",
        "mime_type": "image/jpeg",
        "urls": {
          "original": "http://api.najot.test/cache/images/original/image/c2/30/c7/c230c71b25edf25741dc36eed90cb8509a27364292dda8bf70632a68f71556fa.jpg",
          "100x_": "http://api.najot.test/cache/images/100x_/image/c2/30/c7/c230c71b25edf25741dc36eed90cb8509a27364292dda8bf70632a68f71556fa.jpg",
          "300x_": "http://api.najot.test/cache/images/300x_/image/c2/30/c7/c230c71b25edf25741dc36eed90cb8509a27364292dda8bf70632a68f71556fa.jpg",
          "500x_": "http://api.najot.test/cache/images/500x_/image/c2/30/c7/c230c71b25edf25741dc36eed90cb8509a27364292dda8bf70632a68f71556fa.jpg"
        }
      },
      "translations": [
        {
          "id": 178,
          "name": "Testing 1",
          "locale": "ru"
        },
        {
          "id": 180,
          "name": "Testing 1",
          "locale": "tg"
        },
        {
          "id": 179,
          "name": "Testing 1",
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

## Get single testing

### HTTP Request

`GET https://api.najotapp.uz/v1/testing/{ID}`

```bash
curl --request GET \
  --url http://api.najotapp.uz/v1/testing/{ID}
```

> The above command returns JSON structured like this:

```json
{
  "id": 60,
  "questions": [
    {
      "id": 104,
      "choices": [
        {
          "translations": {
            "ru": {
              "name": "Choice 1"
            },
            "uz": {
              "name": "Choice 1"
            },
            "tg": {
              "name": "Choice 1"
            }
          },
          "weight": 10
        },
        {
          "translations": {
            "ru": {
              "name": "Choice 2"
            },
            "uz": {
              "name": "Choice 2"
            },
            "tg": {
              "name": "Choice 2"
            }
          },
          "weight": 30
        }
      ],
      "translations": [
        {
          "id": 310,
          "question": "Question 1",
          "locale": "ru"
        },
        {
          "id": 312,
          "question": "Question 1",
          "locale": "tg"
        },
        {
          "id": 311,
          "question": "Question 1",
          "locale": "uz"
        }
      ],
      "new_translations": null,
      "current_locale": "ru",
      "default_locale": "ru"
    },
    {
      "id": 106,
      "choices": [
        {
          "translations": {
            "ru": {
              "name": "Choice 1"
            },
            "uz": {
              "name": "Choice 1"
            },
            "tg": {
              "name": "Choice 1"
            }
          },
          "weight": 20
        },
        {
          "translations": {
            "ru": {
              "name": "Choice 2"
            },
            "uz": {
              "name": "Choice 2"
            },
            "tg": {
              "name": "Choice 2"
            }
          },
          "weight": 30
        }
      ],
      "translations": [
        {
          "id": 316,
          "question": "Question 2",
          "locale": "ru"
        },
        {
          "id": 318,
          "question": "Question 2",
          "locale": "tg"
        },
        {
          "id": 317,
          "question": "Question 2",
          "locale": "uz"
        }
      ],
      "new_translations": null,
      "current_locale": "ru",
      "default_locale": "ru"
    }
  ],
  "results": [
    {
      "interval": {
        "min": 0,
        "max": 40
      },
      "translations": {
        "ru": {
          "title": "Title 1",
          "description": "Desc 1"
        },
        "uz": {
          "title": "Title 1",
          "description": "Desc 1"
        },
        "tg": {
          "title": "Title 1",
          "description": "Desc 1"
        }
      }
    },
    {
      "interval": {
        "min": 40,
        "max": 70
      },
      "translations": {
        "ru": {
          "title": "Title 2",
          "description": "Desc 2"
        },
        "uz": {
          "title": "Title 2",
          "description": "Desc 2"
        },
        "tg": {
          "title": "Title 2",
          "description": "Desc 2"
        }
      }
    }
  ],
  "image": {
    "id": 10,
    "original_name": "Colour6",
    "mime_type": "image/jpeg",
    "urls": {
      "original": "http://api.najot.test/cache/images/original/image/c2/30/c7/c230c71b25edf25741dc36eed90cb8509a27364292dda8bf70632a68f71556fa.jpg",
      "100x_": "http://api.najot.test/cache/images/100x_/image/c2/30/c7/c230c71b25edf25741dc36eed90cb8509a27364292dda8bf70632a68f71556fa.jpg",
      "300x_": "http://api.najot.test/cache/images/300x_/image/c2/30/c7/c230c71b25edf25741dc36eed90cb8509a27364292dda8bf70632a68f71556fa.jpg",
      "500x_": "http://api.najot.test/cache/images/500x_/image/c2/30/c7/c230c71b25edf25741dc36eed90cb8509a27364292dda8bf70632a68f71556fa.jpg"
    }
  },
  "translations": [
    {
      "id": 178,
      "name": "Testing 1",
      "locale": "ru"
    },
    {
      "id": 180,
      "name": "Testing 1",
      "locale": "tg"
    },
    {
      "id": 179,
      "name": "Testing 1",
      "locale": "uz"
    }
  ],
  "new_translations": null,
  "current_locale": "ru",
  "default_locale": "ru"
}
```

## Check scores by user

<aside class=warning>
This request requires authentication (X-AUTH-TOKEN header with Device Id)
</aside>

### HTTP Request

`GET https://api.najotapp.uz/v1/testings/{ID}/scores`

```bash
curl --request GET \
  --url http://api.najotapp.uz/v1/testings/{ID}/scores \
  --header 'X-AUTH-TOKEN: qweqweqweqe123123dasd'
```

> The above command returns JSON structured like this:

```json
{
  "id": 8,
  "total_weight": 40,
  "answers": [
    {
      "id": 11,
      "testing_question": 104,
      "answer": "0"
    },
    {
      "id": 12,
      "testing_question": 106,
      "answer": "1"
    }
  ],
  "created_at": "2020-11-16T12:40:44Z",
  "updated_at": "2020-11-16T12:40:44Z"
}
```

## Complete testing by user

<aside class=warning>
This request requires authentication (X-AUTH-TOKEN header with Device ID)
</aside>

### HTTP Request

`POST https://api.najotapp.uz/v1/testings/{ID}/complete`

### Post data

Parameter | Default | Description
--------- | ------- | -----------
answers | none | Array of answers. Answer is the index of the choices

```bash
curl --request POST \
  --url http://api.najotapp.uz/v1/testings/{ID}/complete \
  --header 'content-type: application/json' \
  --header 'x-auth-token: qweqweqweqe123123dasd' \
  --data '{
      "answers": [
        {
          "testingQuestion": {QUESTION_ID},
          "answer": 0
        },
        {
          "testingQuestion": {QUESTION_ID},
          "answer": 2
        },
        {
          "testingQuestion": {QUESTION_ID},
          "answer": 1
        }
      ]
    }'
```

> The above command returns JSON structured like this:

```json
{
  "id": 8,
  "total_weight": 40,
  "answers": [
    {
      "id": 11,
      "testing_question": 104,
      "answer": "0"
    },
    {
      "id": 12,
      "testing_question": 106,
      "answer": "1"
    }
  ],
  "created_at": "2020-11-16T12:40:44Z",
  "updated_at": "2020-11-16T12:40:44Z"
}
```
