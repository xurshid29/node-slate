# Regions

## Get administrative areas

### HTTP Request

`GET https://api.najotapp.uz/v1/regions/administrative-areas`

```bash
curl --request GET \
  --url https://api.najotapp.uz/v1/regions/administrative-areas
```

> The above command returns JSON structured like this:

```json
[
  "Toshkent shahri",
  "Toshkent viloyati",
  "Sirdaryo viloyati",
  "Jizzax viloyati",
  "Samarqand viloyati",
  "Farg'ona viloyati",
  "Namangan viloyati",
  "Andijon viloyati",
  "Qashqadaryo viloyati",
  "Surxondaryo viloyati",
  "Buxoro viloyati",
  "Navoiy viloyati",
  "Xorazm viloyati",
  "Qoraqalpog'iston Respublikasi"
]
```


## Get localities by administrative area

### HTTP Request

`GET https://api.najotapp.uz/v1/regions/localities?administrative-area=Xorazm viloyati`

```bash
curl --request GET \
  --url https://api.najotapp.uz/v1/regions/localities?administrative-area=Xorazm viloyati
```

> The above command returns JSON structured like this:

```json
[
  "Xazorasp tumani",
  "Yangiariq tumani",
  "Gurlan tumani",
  "Urganch tumani",
  "Shovot tumani",
  "Xonqa tumani",
  "Bog‘ot tumani",
  "Yangibozor tumani",
  "Qo‘shko‘pir tumani",
  "Xiva tumani",
  "Urganch shahri",
  "Xiva shahri"
]
```
