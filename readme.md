<center>
    <img src="./docs/assets/logo.png" width="150">
</center>

## XPOZE

### Architecture
- CLI
    - Acts as a client side broker to connect to gateway and handle back and forth communication
    - Forwards requests coming from the gateway to exposed port in the localhost
- Gateway
    - It's a cloud hosted service and exposes a publicly accessible URL through ingress requests to cli will handled

### considerations
- request headers
- response headers
- body / payload
