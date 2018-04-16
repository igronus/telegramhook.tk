
## telegram.tk :: Set Telegram Webhooks 

Here is ready to use vue.js project. Taken from Charles Okwuagwu's answer at [Stack Overflow](https://stackoverflow.com/questions/42554548/how-to-set-telegram-bot-webhook) and a bit improved.

[[https://github.com/igronus/telegramhook.tk/blob/master/screenshot.png|alt=screenshot]]

### Usage

```
I created a file on my server for conveniently setting up telegram webhooks.

You can use the same file on your server.

(If you need https.) This should be on the same server from which you wish to run the Telegram Bot.

1. Drop this file on the same server you wish to host you bots

2. Ensure the mime-type for .pem is enabled on your webserver

3. Browse to this page on our server

4. Fill the form with your BOT_TOKEN and chosen PORT

5. Upload your certificate file

6. Submit the form
```

### Demo

Live demo could be found (and used) at [telegramhook.tk](http://telegramhook.tk). (NB: no https yet on my server, use with caution and be aware of MiTM.)
