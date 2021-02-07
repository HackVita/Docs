# Python Code Example

```python
import httpx
import asyncio

api_login = "76e28af6695611eb8cc500163ed81d8b"
async with httpx.AsyncClient() as req_base:
    request = await req_base.get("https://sec-31.hackvita.it/METHOD?api_login=" + api_login + "&ETCQUERY")
    if request.status_code == 200:
        print(request.json())
```
