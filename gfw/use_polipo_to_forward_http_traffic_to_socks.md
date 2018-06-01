# Use [Polipo](https://github.com/jech/polipo) To Forward HTTP Traffic To SOCKS

## Linux
### Install
```bash
apt-get install polipo
```
### Run(eg, ShadowSocks)
```bash
polipo socksParentProxy=localhost:1080
```

And then
```bash
http_proxy=http://localhost:8123 curl http://www.google.com
https_proxy=https://localhost:8123 curl https://www.google.com
```
HTTP traffic will be forwarded to ShadowSocks

## Windows
### Install
[Solipo](http://serennz.sakura.ne.jp/toybox/solipo/)

### Run
Through GUI

