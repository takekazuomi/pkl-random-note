---
title: tutorial basic config
---

https://pkl-lang.org/main/current/language-tutorial/01_basic_config.html

```sh
$ pkl eval intro.pkl
name = "Pkl: Configure your Systems in New Ways"
attendants = 100
isInteractive = true
amountLearned = 13.37
```

JSON形式で出力

```sh
$ pkl eval -f json intro.pkl
{
  "name": "Pkl: Configure your Systems in New Ways",
  "attendants": 100,
  "isInteractive": true,
  "amountLearned": 13.37
}
```

PropertyList format

```sh
$ pkl eval -f plist intro.pkl
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
  <key>name</key>
  <string>Pkl: Configure your Systems in New Ways</string>
  <key>attendants</key>
  <integer>100</integer>
  <key>isInteractive</key>
  <true/>
  <key>amountLearned</key>
  <real>13.37</real>
</dict>
</plist>
```

Key Valueとして解釈する、値には型があるという感じだろうか。

## Structure: Classes, objects, modules


