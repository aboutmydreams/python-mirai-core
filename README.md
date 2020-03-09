# Mirai Framework Core for Python

Derived from [Python-Mirai](https://github.com/Chenwe-i-lin/python-mirai). If you decided to **Star** this project, please
 also **Star** the original project.

A Flask like Python wrapper of [Mirai-HTTP-API](https://github.com/mamoe/mirai-api-http)

## Installation

### Install from PyPI

``` bash
pip install python-mirai-core
```

### Install from github

``` bash
pip install git+git:://github.com/NatriumLab/python-mirai-core
```

### Features

- Updater handshake with mirai-console automatically when console is restarted or session is expired

- Similar logic to python-telegram-bot or aiogram

- Supports multiple listener for single event, use `return True` to block further calling for this event only

- Supports Websocket (enabled by default)

### Example

Basic example: see demo folder.

Comprehensive example: see [UMR](https://github.com/jqqqqqqqqqq/UnifiedMessageRelay/blob/dev-4.0/src/Driver/Mirai/__init__.py)

Fundamentals: Bot is for sending and Updater is for receiving.

### Thanks 

Thanks [`mamoe`](https://github.com/mamoe) brings us [`mirai`](https://github.com/mamoe/mirai), a tremendous work that 
enables boundless possibilities for QQ Bots. 

### License

[`GNU AGPLv3`](https://choosealicense.com/licenses/agpl-3.0/) 
 
Same as [`mirai`](https://github.com/mamoe/mirai) 
