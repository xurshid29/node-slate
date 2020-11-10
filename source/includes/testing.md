# Testing

## Get testing list

### HTTP Request

`GET https://api.najotapp.uz/v1/testings`

```bash
curl --request GET \
  --url http://api.najot.test/v1/testings
```

> The above command returns JSON structured like this:

```json
{
  "page": 1,
  "items": [
    {
      "id": 13,
      "questions": [
        {
          "correct_choice_weight": 30,
          "id": 93,
          "choices": [
            {
              "translations": {
                "ru": {
                  "name": "ert"
                },
                "uz": {
                  "name": "rtyrty"
                },
                "tg": {
                  "name": "rewr"
                }
              },
              "weight": 10
            },
            {
              "translations": {
                "ru": {
                  "name": "dfgdfg"
                },
                "uz": {
                  "name": "bvcbcvb"
                },
                "tg": {
                  "name": "eqwef"
                }
              },
              "weight": 20
            },
            {
              "translations": {
                "ru": {
                  "name": "cvbsf"
                },
                "uz": {
                  "name": "fewf"
                },
                "tg": {
                  "name": "fasdvc"
                }
              },
              "weight": 30
            }
          ],
          "correct_answer": "2",
          "translations": [
            {
              "id": 277,
              "question": "Ques 1 RU",
              "locale": "ru"
            },
            {
              "id": 279,
              "question": "Ques 1 TG",
              "locale": "tg"
            },
            {
              "id": 278,
              "question": "Ques 1 UZ",
              "locale": "uz"
            }
          ],
          "new_translations": null,
          "current_locale": "ru",
          "default_locale": "ru"
        },
        {
          "correct_choice_weight": 20,
          "id": 95,
          "choices": [
            {
              "translations": {
                "ru": {
                  "name": "sdfsd"
                },
                "uz": {
                  "name": "ggg"
                },
                "tg": {
                  "name": "ddd"
                }
              },
              "weight": 20
            },
            {
              "translations": {
                "ru": {
                  "name": "dsf"
                },
                "uz": {
                  "name": "gfgfg"
                },
                "tg": {
                  "name": "eerererer"
                }
              },
              "weight": 20
            },
            {
              "translations": {
                "ru": {
                  "name": "cxvcx"
                },
                "uz": {
                  "name": "vcb"
                },
                "tg": {
                  "name": "df"
                }
              },
              "weight": 30
            },
            {
              "translations": {
                "ru": {
                  "name": "fdf"
                },
                "uz": {
                  "name": "ffffff"
                },
                "tg": {
                  "name": "gfgfgfg"
                }
              },
              "weight": 40
            }
          ],
          "correct_answer": "1",
          "translations": [
            {
              "id": 283,
              "question": "Ques 2 RU",
              "locale": "ru"
            },
            {
              "id": 285,
              "question": "Ques 2 TG",
              "locale": "tg"
            },
            {
              "id": 284,
              "question": "Ques 2 UZ",
              "locale": "uz"
            }
          ],
          "new_translations": null,
          "current_locale": "ru",
          "default_locale": "ru"
        }
      ],
      "image": {
        "id": 4,
        "original_name": "City8",
        "mime_type": "image/jpeg",
        "urls": {
          "original": "http://api.najot.test/cache/images/original/image/ee/c0/a0/eec0a033d8aaeb4a7a93d433955977a358e7ddf62503d87c77e0ea9cca0ff659.jpg",
          "100x_": "http://api.najot.test/cache/images/100x_/image/ee/c0/a0/eec0a033d8aaeb4a7a93d433955977a358e7ddf62503d87c77e0ea9cca0ff659.jpg",
          "300x_": "http://api.najot.test/cache/images/300x_/image/ee/c0/a0/eec0a033d8aaeb4a7a93d433955977a358e7ddf62503d87c77e0ea9cca0ff659.jpg",
          "500x_": "http://api.najot.test/cache/images/500x_/image/ee/c0/a0/eec0a033d8aaeb4a7a93d433955977a358e7ddf62503d87c77e0ea9cca0ff659.jpg"
        }
      },
      "translations": [
        {
          "id": 37,
          "name": "Test 1 RU",
          "locale": "ru"
        },
        {
          "id": 39,
          "name": "Test 1 TG",
          "locale": "tg"
        },
        {
          "id": 38,
          "name": "Test 1 UZ",
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
  --url http://api.najot.test/v1/testing/{ID}
```

> The above command returns JSON structured like this:

```json
{
  "id": 13,
  "questions": [
    {
      "correct_choice_weight": 30,
      "id": 93,
      "choices": [
        {
          "translations": {
            "ru": {
              "name": "ert"
            },
            "uz": {
              "name": "rtyrty"
            },
            "tg": {
              "name": "rewr"
            }
          },
          "weight": 10
        },
        {
          "translations": {
            "ru": {
              "name": "dfgdfg"
            },
            "uz": {
              "name": "bvcbcvb"
            },
            "tg": {
              "name": "eqwef"
            }
          },
          "weight": 20
        },
        {
          "translations": {
            "ru": {
              "name": "cvbsf"
            },
            "uz": {
              "name": "fewf"
            },
            "tg": {
              "name": "fasdvc"
            }
          },
          "weight": 30
        }
      ],
      "correct_answer": "2",
      "translations": [
        {
          "id": 277,
          "question": "Ques 1 RU",
          "locale": "ru"
        },
        {
          "id": 279,
          "question": "Ques 1 TG",
          "locale": "tg"
        },
        {
          "id": 278,
          "question": "Ques 1 UZ",
          "locale": "uz"
        }
      ],
      "new_translations": null,
      "current_locale": "ru",
      "default_locale": "ru"
    },
    {
      "correct_choice_weight": 20,
      "id": 95,
      "choices": [
        {
          "translations": {
            "ru": {
              "name": "sdfsd"
            },
            "uz": {
              "name": "ggg"
            },
            "tg": {
              "name": "ddd"
            }
          },
          "weight": 20
        },
        {
          "translations": {
            "ru": {
              "name": "dsf"
            },
            "uz": {
              "name": "gfgfg"
            },
            "tg": {
              "name": "eerererer"
            }
          },
          "weight": 20
        },
        {
          "translations": {
            "ru": {
              "name": "cxvcx"
            },
            "uz": {
              "name": "vcb"
            },
            "tg": {
              "name": "df"
            }
          },
          "weight": 30
        },
        {
          "translations": {
            "ru": {
              "name": "fdf"
            },
            "uz": {
              "name": "ffffff"
            },
            "tg": {
              "name": "gfgfgfg"
            }
          },
          "weight": 40
        }
      ],
      "correct_answer": "1",
      "translations": [
        {
          "id": 283,
          "question": "Ques 2 RU",
          "locale": "ru"
        },
        {
          "id": 285,
          "question": "Ques 2 TG",
          "locale": "tg"
        },
        {
          "id": 284,
          "question": "Ques 2 UZ",
          "locale": "uz"
        }
      ],
      "new_translations": null,
      "current_locale": "ru",
      "default_locale": "ru"
    }
  ],
  "image": {
    "id": 4,
    "original_name": "City8",
    "mime_type": "image/jpeg",
    "urls": {
      "original": "http://api.najot.test/cache/images/original/image/ee/c0/a0/eec0a033d8aaeb4a7a93d433955977a358e7ddf62503d87c77e0ea9cca0ff659.jpg",
      "100x_": "http://api.najot.test/cache/images/100x_/image/ee/c0/a0/eec0a033d8aaeb4a7a93d433955977a358e7ddf62503d87c77e0ea9cca0ff659.jpg",
      "300x_": "http://api.najot.test/cache/images/300x_/image/ee/c0/a0/eec0a033d8aaeb4a7a93d433955977a358e7ddf62503d87c77e0ea9cca0ff659.jpg",
      "500x_": "http://api.najot.test/cache/images/500x_/image/ee/c0/a0/eec0a033d8aaeb4a7a93d433955977a358e7ddf62503d87c77e0ea9cca0ff659.jpg"
    }
  },
  "translations": [
    {
      "id": 37,
      "name": "Test 1 RU",
      "locale": "ru"
    },
    {
      "id": 39,
      "name": "Test 1 TG",
      "locale": "tg"
    },
    {
      "id": 38,
      "name": "Test 1 UZ",
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
This request requires authentication (X-AUTH-TOKEN header with firebase session key)
</aside>

### HTTP Request

`GET https://api.najotapp.uz/v1/testings/{ID}/scores`

```bash
curl --request GET \
  --url http://api.najot.test/v1/testings/13/scores \
  --header 'X-AUTH-TOKEN: qweqweqweqe123123dasd'
```

> The above command returns JSON structured like this:

```json
{
  "id": 3,
  "total_weight": 20,
  "answers": [
    {
      "is_correct": false,
      "id": 3,
      "testing_question": 93,
      "answer": "1"
    },
    {
      "is_correct": true,
      "id": 4,
      "testing_question": 95,
      "answer": "1"
    }
  ],
  "created_at": "2020-11-09T19:43:24Z",
  "updated_at": "2020-11-09T19:43:24Z"
}
```

## Complete testing by user

<aside class=warning>
This request requires authentication (X-AUTH-TOKEN header with firebase session key)
</aside>

### HTTP Request

`POST https://api.najotapp.uz/v1/testings/{ID}/complete`

### Post data

Parameter | Default | Description
--------- | ------- | -----------
answers | none | Array of answers. Answer is the index of the choices

```bash
curl --request POST \
  --url http://api.najot.test/v1/testings/{ID}/complete \
  --header 'content-type: application/json' \
  --header 'x-auth-token: qweqweqweqe123123dasd' \
  --data '{
  "answers": [
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
  "id": 5,
  "total_weight": 20,
  "answers": [
    {
      "is_correct": false,
      "id": 7,
      "testing_question": 93,
      "answer": "1"
    },
    {
      "is_correct": true,
      "id": 8,
      "testing_question": 95,
      "answer": "1"
    }
  ],
  "created_at": "2020-11-10T11:45:53Z",
  "updated_at": "2020-11-10T11:45:53Z"
}
```
