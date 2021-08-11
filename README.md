# python-logger
Custom python logger that can connect system outputs to log files and discord webhooks purely without unwanted logs when using python's built-in logger library (or any other library that basically just uses python's library under the hood).

You should be able to easily use the logger by downloading `discordpylogger.py` and editting the the file names and file modes (write or append) you want to use and set the webhook url you want to use for logs.

Then you can import the module in your main file.

```py
import discordpylogger
```
