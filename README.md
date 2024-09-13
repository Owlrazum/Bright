# Скачать

Scratch офлайн быстрее из Microsoft Store \
[https://downloads.scratch.mit.edu/desktop/Scratch%20Setup.exe](https://apps.microsoft.com/detail/9pfgj25jl6x3?cid=storebadge&ocid=badge&rtc=1&hl=ru-kg&gl=KG)

https://github.com/godotengine/godot/releases/download/4.3-stable/Godot_v4.3-stable_win64.exe.zip

Драйвер для Arduino IDE, не уверен что нужен \
https://wiki.amperka.ru/_media/articles:driver-ch340:ch340ser-windows.zip

Microsoft Store удобнее \
[https://www.python.org/ftp/python/3.12.6/python-3.12.6-amd64.exe](https://www.microsoft.com/store/productId/9NCVDN91XZQP?ocid=pdpshare)

https://www.mozilla.org/ru/firefox/download/thanks/

https://discord.com/api/downloads/distributions/app/installers/latest?channel=stable&platform=win&arch=x64

https://code.visualstudio.com/sha/download?build=stable&os=win32-x64

## Необязательно

### gh, git
```
winget install --id GitHub.cli
winget install --id Git.Git -e --source winget
```
# Настроить

### Закрепить вкладки в Firefox:

1. https://typerun.top/#rus_adv
2. https://kahoot.it/
3. https://www.google.com/search?client=firefox-b-d&q=snake+game
4. https://docs.godotengine.org/en/stable/getting_started/introduction/introduction_to_godot.html#
5. https://www.onlinegdb.com/online_c++_compiler
6. https://codeforces.com/problemset?tags=-800

### Запретить сайты

Redirect prohibited domains to localhost:
```
Add-Content -Path C:\Windows\System32\drivers\etc\hosts -Value "
127.0.0.1 pornhub.com
127.0.0.1 roblox.com
127.0.0.1 yandex.ru
127.0.0.1 vseigru.net
127.0.0.1 igroutka.ru
127.0.0.1 bluestacks.com
127.0.0.1 youtube.com
"
```
Flush DNS:
```
ipconfig /flushdns
```
Clear firefox cache: History -> Clear recent history -> Ensure cache is checked

Check hosts file:
```
Get-Content -Path C:\Windows\System32\drivers\etc\hosts
```
