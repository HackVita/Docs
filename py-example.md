# Python Code Example

```python
import requests

api_login = "76e28af6695611eb8cc500163ed81d8b"
# Your API-Key here.
method = "METHOD"
# The API method that you want to use.
parameters = {
    "api_login": api_login,
    # Other parameters here ("key": "value").
}

result = requests.get(f"https://sec-31.hackvita.it/{method}", params=parameters)
print(result.json())
```
___The code was provided by [@CrisMystik](https://t.me/crismystik)___
