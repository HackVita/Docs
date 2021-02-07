# PHP Code Example

```php
$api_login = "76e28af6695611eb8cc500163ed81d8b";
$request = curl_init();
curl_setopt($request, CURLOPT_RETURNTRANSFER, true);
curl_setopt($request, CURLOPT_URL, "https://sec-31.hackvita.it/x?api_login=".$api_login."&y");
$response = curl_exec($request);
$response = json_decode($response);
curl_close($request);
if($response['ok']){
  echo 'OK!';
}else{
  echo 'OH NO!';
}
```
