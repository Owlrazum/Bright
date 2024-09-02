# Задачи до пятницы

- Написать и сдать КТП с титульным листом
- Запрос на новое оборудавание и замена старого
- Проверить все компы в 104 и 106
- Скачать нужные программы на каждый комп. Скачать Godot, Git, Gh, GCC Compiller, package manager for windows
- Запретить скачивать игры или программы на компьютере, но оставить возможность для терминала
- Проверить работу терминала

# Что устанавливать

### Вручную
- Godot https://github.com/godotengine/godot/releases/download/4.3-stable/Godot_v4.3-stable_win64.exe.zip
- Visual Studio C/C++ compiler https://visualstudio.microsoft.com/ru/thank-you-downloading-visual-studio/?sku=Community&channel=Release&version=VS2022&source=VSLandingPage&cid=2030&passive=false
(Нужна проставить четыре галочки, 3 как на скрине и одна на "Основные компоненты C++")
![visual studio](https://github.com/user-attachments/assets/9a2e9e4e-2a87-4b8a-9eea-af864fd435fa)

### Через winget
```
winget install --id GitHub.cli
winget install --id Git.Git -e --source winget
winget install -e --id Python.Python.3.12
```

