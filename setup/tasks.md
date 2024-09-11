# Задачи до пятницы

- Написать и сдать КТП с титульным листом
- Запрос на новое оборудавание и замена старого
- Проверить все компы в 104 и 106
- Запретить скачивать игры или программы на компьютере, но оставить возможность для терминала

# Что устанавливать

### Вручную
- Godot https://github.com/godotengine/godot/releases/download/4.3-stable/Godot_v4.3-stable_win64.exe.zip

### Через winget
```
winget install --id GitHub.cli
winget install --id Git.Git -e --source winget
winget install -e --id Python.Python.3.12
```

# Как запретить

Установить Edit group policy для Home версии Windows
```
Get-ChildItem @(
>>     "C:\Windows\servicing\Packages\Microsoft-Windows-GroupPolicy-ClientTools-Package*.mum",
>>     "C:\Windows\servicing\Packages\Microsoft-Windows-GroupPolicy-ClientExtensions-Package*.mum"
>> ) | ForEach-Object { dism.exe /online /norestart /add-package:"$_" }
```

Ctrl + R -> Gpedit.msc
https://winitpro.ru/index.php/2015/10/02/redaktor-gruppovyx-politik-dlya-windows-10-home-edition/
