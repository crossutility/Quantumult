# One Tap to Configure Quantumult (Since Version 2.2.3)

## URI Scheme:

```
quantumult://configuration?server=websafe-base64-encode-utf8-no-padding(favorites-server-https-link)&filter=websafe-base64-encode-utf8-no-padding(favorites-filter-https-link)&rejection=websafe-base64-encode-utf8-no-padding(favorites-rejection-https-link)
```

### Sample:

The response content of "favorites-server-https-link" follows the style of SSR subscription, if the server type is SS, then the server info in the content should follow the [SS-URI](https://shadowsocks.org/en/spec/SIP002-URI-Scheme.html) 

- Links
```
https://raw.githubusercontent.com/crossutility/Quantumult/master/samples/quantumult-server.txt
https://raw.githubusercontent.com/crossutility/Quantumult/master/samples/quantumult-filter.txt
https://raw.githubusercontent.com/crossutility/Quantumult/master/samples/quantumult-rejection.txt
```

- Quantumult-URI
```
quantumult://configuration?server=aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2Nyb3NzdXRpbGl0eS9RdWFudHVtdWx0L21hc3Rlci9zYW1wbGVzL3F1YW50dW11bHQtc2VydmVyLnR4dA&filter=aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2Nyb3NzdXRpbGl0eS9RdWFudHVtdWx0L21hc3Rlci9zYW1wbGVzL3F1YW50dW11bHQtZmlsdGVyLnR4dA&rejection=aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2Nyb3NzdXRpbGl0eS9RdWFudHVtdWx0L21hc3Rlci9zYW1wbGVzL3F1YW50dW11bHQtcmVqZWN0aW9uLnR4dA
```
```    
quantumult://configuration?server=aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2Nyb3NzdXRpbGl0eS9RdWFudHVtdWx0L21hc3Rlci9zYW1wbGVzL3F1YW50dW11bHQtc2VydmVyLnR4dA
```
