# Generate an account from the private generator

You can generate as many daily private accounts as your plan allows.

# Example request

`https://sec-31.hackvita.it/generatePrivateAccount?login_key=APIKEY&gen_id=GENERATORID`

# Successful response

Parameter | Description
--------- | -----------
alt | The account and password, in the form of `username:password`.

```json
{
  "ok": true,
  "alt": "friends@hackvita.it:whatareyoudoing"
}
```
