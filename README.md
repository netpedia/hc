# hc
HTTP Custom Payload

```sh
GET /cdn-cgi/trace HTTP/1.1[crlf]Host: cdn.noice.id[crlf][crlf]CF-RAY / HTTP/1.1[crlf]Host: [host][crlf]Upgrade: websocket[crlf]Connection: keep-alive[crlf]User-Agent: [ua][crlf]Upgrade: websocket[crlf][crlf]
```
Remote Proxy
```sh
104.18.2.198:443
```
SNI/SSL/[host]
```sh
netpediahostserver
```
Result
```sh
GET /cdn-cgi/trace HTTP/1.1\r\nHost: cdn.noice.id\r\n\r\nCF-RAY / HTTP/1.1\r\nHost: net.datapedia.web.id\r\nUpgrade: websocket\r\nConnection: keep-alive\r\nUser-Agent: Mozilla/5.0 (Linux; Android 11; Infinix X6812B Build/RP1A.200720.011; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/114.0.5735.131 Mobile Safari/537.36\r\nUpgrade: websocket\r\n\r\n

connected to socket 104.18.2.198:443
```

## Xl
* [noice](./xl/noice.hc)
* [akrab](./xl/akrab.hc)

## By.U
* [26](./byu/26.hc)
* [52](./byu/52.hc)
* [5 mei](./byu/byu1.hc)
* [3 mei](./byu/byuopok.hc)


## Tsel
* [opok 23 Mei 2023](./tsel/23meiopoktsel.hc)
