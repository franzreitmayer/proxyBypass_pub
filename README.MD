# ProxyBypass

## Description
The start page /static/index.html offers an input field to enter the wanted download url. The post endpoint /byUrl of app.js downloads the file using the axios framework and converts its content to base64. This base64 string is rendered into the resonse html in javascript. This javascipt routine converts the base64 string back into binary data and offers the binary as **local** download as the response already passed the proxy. This way the binary is masqueraded to the proxy.
The image below gives and overwiew:
![overview](https://github.com/franzreitmayer/proxyBypass_pub/blob/d6952064708c8de64d8f5f558c01bd7096570173/doc/images/ProxyBypass-Description.gif)