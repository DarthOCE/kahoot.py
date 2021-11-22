![Header](./header.png)
<h1 align="center">Kahoot.py</h1>
<p align="center">Basic python Kahoot API</p>

<h1 align="center">Installation</h1>

`pip install -U kahoot.py`

```py
from kahoot.py import client
bot = client()
bot.join(12345,"KahootPY")
def joinHandle():
  pass
bot.on("joined",joinHandle)
```

Since this is basically a translation of JavaScript to Python, expect issues and bugs.

Documentation:
See [kahoot.js-updated](https://github.com/DarthOCE/kahoot.py/blob/main/Documentation.md). The API is very similar, besides having no Promises.


![Footer](./footer.png)
