# vagabot-simple
Simplified vagabot which supports server and player lists

See the original here:
https://github.com/edencomputing/vagabot


Using libraries provided by Alta VR:

- ATT Websocket bot: https://github.com/alta-vr/ATT-Bot-JS

- ATT websocket connection library: https://github.com/alta-vr/att-websockets

- Alta VR jsapi: https://github.com/alta-vr/alta-jsapi


### Usage

To start, install node/npm by following the excellent guide prepared by Joel here:

https://paper.dropbox.com/doc/An-Introduction-to-ATT-Bots-sN2e61qvfnQ3yb7uoGbL5

In short,
1. Install node/npm using the many methods available online.
2. Install dependencies with `npm i`


The bot uses some JSON configuration files.  You may copy the *.example files provided in the checkout, or create your own.

- **credentials.json** - this file contains the authentication information to connect to Alta API and to Discord
```
{
    "username" : "<your ATT username>",
    "password" : "<your ATT password>",
    "botToken" : "<your bot's discord token>"
}
```

Once configured, start the bot with:

```npm start```