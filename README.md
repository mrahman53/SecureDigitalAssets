# Project-4

Secure Digital Assets on a Private Blockchain


```
### Run
``` 
$ node server.js
```
### View application
``` 
http://localhost:8000
```

Available Endpoints to Hit:

- Star registration Endpoint  - POST - /block
- Star Lookup by height       - GET - /block/:height
- Star Lookup by address      - GET - /stars/address:address
- Star Lookup by hash         - GET - /stars/hash:hash
- Blockchain ID validation routine -  POST - /requestValidation
- Validate message signature - POST - /message-signature/validate