[![](https://img.shields.io/badge/OS-MacOS-blue.svg?longCache=True)]()
[![](https://img.shields.io/pypi/pyversions/growlnotify.svg?longCache=True)](https://pypi.org/pypi/growlnotify/)
[![](https://img.shields.io/pypi/v/growlnotify.svg?maxAge=3600)](https://pypi.org/pypi/growlnotify/)
[![Travis](https://api.travis-ci.org/looking-for-a-job/growlnotify.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/growlnotify.py/)

#### Install
```bash
$ [sudo] pip install growlnotify
```

#### Functions
function|description
-|-
`growlnot.args(**kwargs)`|return list with `growlnotify` cli arguments
`growlnot.notify(**kwargs)`|run growlnotify

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

<p align="center"><a href="https://pypi.org/project/readme-md/">readme-md</a> - README.md generator</p>