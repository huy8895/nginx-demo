1. postman:

- origin 
```bash
curl --location 'https://postman-echo.com/get?foo1=bar1&foo2=bar2'
```

- forward qua nginx:
```bash
curl --location 'localhost/postman-echo/get?foo1=bar1&foo2=bar2' 
```