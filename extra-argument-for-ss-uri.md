# Extra Argument for SS-URI

Quantumult supports argument "group" for additional usage. Even this is the unsupported argument of official SS-URI, Quantumult needs to follow the [SIP002 SS-URI Scheme](https://shadowsocks.org/en/spec/SIP002-URI-Scheme.html).

## SS-URI

ss://YmYtY2ZiOnRlc3Q@192.168.100.1:8888/?plugin=url-encoded-plugin-argument-value&group=websafe-base64-encode-utf8-groupname&unsupported-arguments=should-be-ignored#Dummy+profile+name

The reason to encode the group name is for the compatibility of the SSR-URI.

### Sample:
```
ss://YmYtY2ZiOnRlc3Q=@192.168.100.1:8888/?plugin=obfs-local%3Bobfs%3Dhttp%3Bobfs-host%3Dbing.com&group=Z3JvdXBuYW1l#Server-1
```
