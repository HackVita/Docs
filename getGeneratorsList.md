# Get the list of generators

By "generators" here we mean the list you can find by pressing on "account list" in the panel.

# Example request

`https://sec-31.hackvita.it/getGeneratorsList?login_key=APIKEY`

# Successful response

Parameter | Description
--------- | -----------
id | the id of the generator, can be used for example with the methods of the generations
name | the name of the generator
link | the link of the generator
private | is the generator private? (bool)

```json
{
  "ok":true,
  "private" : [
    {
      "id": 6,
      "name": "Disney+",
      "link": "https://www.disneyplus.com/",
      "private": 1
    },
    "..."
  ],
  "public" : [
    "..."
  ]
}
```
