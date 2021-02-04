# Generate an account from the public generator

You can generate as many daily accounts as your plan allows.

# Example request

`https://sec-31.hackvita.it/generatePublicAccount?login_key=APIKEY&gen_id=GENERATORID`

# Successful response

Parameter | Description
--------- | -----------
alt | The account and password, in the form of `username:password`.

```json
{
  "ok": true,
  "alt": "hello@hackvita.it:hackvitatopgenerator2021"
}
```
