<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/growlnotify.svg?maxAge=3600)](https://pypi.org/project/growlnotify/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/growlnotify.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/growlnotify.py/actions)

### Installation
```bash
$ [sudo] pip install growlnotify
```

#### Examples
```python
>>> import growlnotify
>>> growlnotify.notify(t="title",m="message")           # -t "title" -m "message"
>>> growlnotify.notify(title="title",message="message") # --title "title" --message "message"
```

`-s`, `--sticky`
```python
>>> growlnotify.notify(title="title",s=True)       # -s
>>> growlnotify.notify(title="title",sticky=True)  # --sticky
```

growlnotify keys
```bash
$ growlnotify --help
```

#### Links
+   [growl.info](http://growl.info/)

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
