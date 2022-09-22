```./httpie post https://httpbin.org/post greeting=hola name=world```

```
HTTP/1.1 200 OK

date: ""
content-type: "application/json"
content-length: "509"
connection: "keep-alive"
server: "gunicorn/19.9.0"
access-control-allow-origin: "*"
access-control-allow-credentials: "true"
{
  "args": {},
  "data": "{\"greeting\":\"hola\",\"name\":\"world\"}",
  "files": {},
  "form": {},
  "headers": {
    "Accept": "*/*",
    "Content-Length": "36",
    "Content-Type": "application/json",
    "Host": "httpbin.org",
    "User-Agent": "Rust Httpie",
    "X-Amzn-Trace-Id": "Root=1-632befe5-3b3315b613d16a3a35269e15",
    "X-Powered-By": "Rust"
  },
  "json": {
    "greeting": "hola",
    "name": "world"
  },
  "origin": "",
  "url": "https://httpbin.org/post"
}
```