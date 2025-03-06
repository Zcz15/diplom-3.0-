# diplom
 diplom — це 2D-платформер, де гравець керує фіном з часу пригод, долаючи ворогів та перешкоди.

## Функціонал:
- Управління персонажем за допомогою клавіш.
- Різноманітні рівні та вороги.
- Використання меча та луку.
- руйнуючийся об'єкт і ефекти.

## Як запустити:
1. Відкрити проєкт у Unity (версія 2021+).
2. Запустити сцену `MainScene`.
3. Насолоджуватися грою!



Опис проєкту
"diplom" – це 2D-платформер у жанрі пригодницького екшену. Гравець керує лицарем, який проходить рівні, бореться з ворогами та збирає ресурси.

🛠️ Встановлення та запуск
1️⃣ Клонування репозиторію
bash
Copy
Edit
git clone https://github.com/Zcz15/diplom-3.0-.git
cd diplom-3.0-
Встановлення залежностей
Для Unity:
Встановити Unity Hub
Відкрити Unity Hub, додати проєкт:
"Open Project" → Вибрати папку diplom-3.0-
Дочекатися завантаження залежностей
Для MonoGame:
Встановити .NET SDK
Встановити MonoGame:
bash
Copy
Edit
dotnet new -i MonoGame.Templates.CSharp
Відкрити проєкт у Visual Studio та зібрати рішення:
bash
Copy
Edit
dotnet build
3️⃣ Запуск проєкту
Для Unity:
Відкрити Unity Hub
Запустити сцену з Editor → Play
Для MonoGame:
bash
Copy
Edit
dotnet run
📁 Структура проєкту
bash
Copy
Edit
diplom-3.0-/
│── Assets/           # Графіка, звуки, анімації
│── Scripts/          # Код гри (C#)
│── Scenes/           # Рівні гри (Unity)
│── Config/           # Налаштування гри
│── Docs/             # Документація
│── .gitignore        # Ігнорує зайві файли в Git
│── README.md         # Цей файл
│── diplom-3.0-Game.sln    # Файл рішення (MonoGame)
│── diplom-3.0-Game.csproj # Проєкт MonoGame
│── Game.cs           # Головний код гри
🛠 Базові команди Git
bash
Copy
Edit
# Створення нової гілки
git checkout -b new-feature

# Додавання змін у коміт
git add .
git commit -m "Додав новий рівень у гру"

# Відправка коду на GitHub
git push origin new-feature
🚀 Розгортання (для продакшну)
Для Unity (Build & Export):
Відкрити Unity
File → Build Settings → Вибрати платформу (Windows, WebGL тощо)
Натиснути "Build"
Для MonoGame:
bash
Copy
Edit
dotnet publish -c Release -r win-x64 --self-contained
(Це створить .exe файл у папці bin/Release/net7.0/win-x64/)

📜 Ліцензія
Проєкт ліцензований під MIT License.

