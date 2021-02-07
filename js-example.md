# JavaScript Code Example

```javascript
var api_login = "YOUR_API_KEY";
let request = new XMLHttpRequest();
request.open("GET", "https://sec-31.hackvita.it/METHOD?api_login=" + api_login + "&ETCQUERY", true);
request.send();
request.addEventListener("readystatechange", function () {
    if (this.readyState === 4 && this.status == 200) {
        element = JSON.parse(request.responseText);
        console.log(element);
    }
});
```
