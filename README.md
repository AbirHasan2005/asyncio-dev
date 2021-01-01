## Pyrogram Asyncio-Dev Branch

<p align="center">
    <a href="https://github.com/pyrogram/pyrogram">
        <img src="https://i.imgur.com/BOgY9ai.png" alt="Pyrogram">
    </a>
### Please dont fork this !!Instead fork the original source of pyrogram and support there work 😟
    <br>
    <b>Telegram MTProto API Framework for Python</b>
    <br>
    <a href="https://docs.pyrogram.org">
        Documentation
    </a>
    •
    <a href="https://github.com/pyrogram/pyrogram/releases">
        Releases
    </a>
    •
    <a href="https://t.me/Pyrogram">
        Community
    </a>
</p>

## Pyrogram

```python
from pyrogram import Client, Filters

app = Client("my_account")


@app.on_message(Filters.private)
def hello(client, message):
    message.reply_text("Hello {}".format(message.from_user.first_name))


app.run()
```

**Pyrogram** is an elegant, easy-to-use [Telegram](https://telegram.org/) client library and framework written from the
ground up in Python and C. It enables you to easily create custom apps for both user and bot identities (bot API alternative) via the [MTProto API](https://core.telegram.org/api#telegram-api).
