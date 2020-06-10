# api-dev-kit
## Description
The API Developer Kit helps with developing APIs by giving you control over fetch (POST and GET) without having to write code. This allows you to test client side interaction with the server before you really write code and ebed it in a page. 
## Installation
Please note that you will have to add `sudo` in some cases
```bash
git clone https://github.com/maxwellmatthis/api-dev-kit.git && cd api-dev-kit
```
## Usage
Everything is in one HTML file. Just open it in a browser. 
Since some operating systems (such as MacOS or Windows) only allow localhost processes to interact with themselves you may experience some difficulties trying to access a localhost API or page in development. To fix this problem copy `api-dev-kit.html` to the static directory (where css and js files go) of that server. 