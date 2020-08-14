# api-dev-kit
## Description
The API Developer Kit helps with developing APIs and Socket.io Aplications by giving you control over fetch (POST and GET) and socket.io-client without having to write code. This allows you to test client side interaction with the server before you write the production logic.
## Installation
Please note that you will have to add `sudo` in some cases
```bash
git clone https://github.com/maxwellmatthis/api-dev-kit.git && cd api-dev-kit
```
## Usage
Everything is in one HTML file. Just open it in a browser. 
If you are trying to work with a local API you might need to use Cross-Origin Resource Sharing to access it. 
__Note:__ To use the socket.io features you will need to be connected to the internet since the kit uses cloudflare CDN to get the newest socket.io-client version.