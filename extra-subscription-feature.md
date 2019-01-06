
# Extra Server Subscription Feature
Quantumult will check HTTP response header for additional informations. 

## Response Header to Check

```
Subscription-Userinfo: upload=2375927198; download=12983696043; total=1099511627776
```

## Sample

```
HTTP/1.1 200 OK
Accept-Ranges: bytes
Connection: keep-alive
Content-Length: 356
Content-Type: text/plain
Date: Sun, 26 Oct 2018 04:46:33 GMT
ETag: "5bc27681-164"
Last-Modified: Sat, 13 Oct 2018 22:49:37 GMT
Server: nginx
Strict-Transport-Security: max-age=31536000; includeSubDomains
Subscription-Userinfo: upload=2375927198; download=12983696043; total=1099511627776
```

## Beta
The `expire=1862111613` is the seconds from 00:00:00 UTC, January 1, 1970

```
Subscription-Userinfo: upload=2375927198; download=12983696043; total=1099511627776; expire=1862111613
```
