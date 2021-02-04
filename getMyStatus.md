# Get your informations

You can get generator information by using the ID that is for example proposed to you in [/getGeneratorsList](getGeneratorsList).

# Example request

`https://sec-31.hackvita.it/getInformationsAboutGeneratorID?login_key=APIKEY&gen_id=GENERATORID`

# Successful response

Parameter | Description
--------- | -----------
username | your username
email | your email
id | associated id
detected_language | language detected at registration
credits | your credits
generations | information regarding generations

```json
{
  "ok": true,
  "informations": {
    "username": "hackvita",
    "email": "egg@hackvita.it",
    "id": "eggsaregood",
    "detected_language": "en",
    "credits": 50,
    "generations": {
      "total_generations_for_plan_public": 0,
      "total_generations_for_plan_private": 0,
      "total_generations_for_you_public": 0,
      "total_generations_for_you_private": 0
    }
  }
}
```
