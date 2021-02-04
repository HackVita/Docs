# Get the information of a generator type

You can get generator information by using the ID that is for example proposed to you in [/getGeneratorsList](getGeneratorsList).

# Example request

`https://sec-31.hackvita.it/getInformationsAboutGeneratorID?login_key=APIKEY&gen_id=GENERATORID`

# Successful response

Parameter | Description
--------- | -----------
generator_id | the ID of the generator
generator_name | the name of the generator
service_link | the link of the generator
is_generator_private | is generator private? (bool)

```json
{
  "ok": true,
  "informations": {
    "generator_id": 6,
    "generator_name": "Disney+",
    "service_link": "https://www.disneyplus.com/",
    "is_generator_private": true
  }
}
```
