# 1. Установить через флешку

Scratch, Paint3D, Python 3.12 вручную через Microsoft Store

Убрать Дискорд из автозапуска  

Открепите лишнее с панели задач, уберите "ярлык" в названиях "Paint 3D" и "Scratch" при отправке с `shell:AppsFolder`

```
net user Visitor /delete ; net user ST-00 /add
```

# 2. Запрет сайтов
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

Check hosts file:
```
Get-Content -Path C:\Windows\System32\drivers\etc\hosts
```

# 3. Закрепите вкладки в Firefox

1. https://typerun.top/#rus_adv
2. https://kahoot.it/
3. https://www.google.com/search?client=firefox-b-d&q=snake+game
4. https://docs.godotengine.org/en/stable/getting_started/introduction/introduction_to_godot.html#
5. https://www.onlinegdb.com/online_c++_compiler
6. https://codeforces.com/problemset?tags=-800

# Дополнительно: 

## Установка онлайн

[Arduino IDE](https://downloads.arduino.cc/arduino-ide/arduino-ide_2.3.2_Windows_64bit.exe) \
[VS Code](https://code.visualstudio.com/sha/download?build=stable&os=win32-x64) 

Microsoft Store удобнее: \
[Scratch](https://apps.microsoft.com/detail/9pfgj25jl6x3?cid=storebadge&ocid=badge&rtc=1&hl=ru-kg&gl=KG) \
[Python](https://www.microsoft.com/store/productId/9NCVDN91XZQP?ocid=pdpshare) 

[Discord](https://discord.com/api/downloads/distributions/app/installers/latest?channel=stable&platform=win&arch=x64) \
[Godot](https://github.com/godotengine/godot/releases/download/4.3-stable/Godot_v4.3-stable_win64.exe.zip) 

[Firefox](https://www.mozilla.org/ru/firefox/download/thanks/) \
[Chrome](https://www.google.com/intl/ru/chrome/next-steps.html?statcb=1&installdataindex=empty&defaultbrowser=0#) 

## gh, git
```
winget install --id GitHub.cli
winget install --id Git.Git -e --source winget
```

## Дополнительно: Запретить сайты


Flush DNS:
```
ipconfig /flushdns
```
Clear firefox cache: History -> Clear recent history -> Ensure cache is checked

## Активация окон

https://massgrave.dev/

Не уверен что метод ниже активрирует навсегда:
```
slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX && slmgr /skms kms8.msguides.com && slmgr /ato
```



