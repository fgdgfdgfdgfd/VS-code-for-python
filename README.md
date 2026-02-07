# ⚡ VS Code for Python

> 🐍 A full clone of Visual Studio Code built with Python

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Python](https://img.shields.io/badge/python-3.8+-green)
![License](https://img.shields.io/badge/license-MIT-yellow)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey)

---

## 🌐 Language / Язык

- [🇬🇧 English](#-english)
- [🇷🇺 Русский](#-русский)

---

# 🇬🇧 English

## ✨ Features

| Feature | Status |
|---------|--------|
| 📝 Code editor with syntax highlighting | ✅ |
| 📂 File explorer with tree view | ✅ |
| 📑 Tab system | ✅ |
| 💻 Built-in terminal | ✅ |
| 🔍 Search across files | ✅ |
| 🗺️ Code minimap | ✅ |
| 📋 Menu bar | ✅ |
| 📊 Status bar | ✅ |
| 📌 Activity bar | ✅ |
| 🏠 Welcome tab | ✅ |
| 🎨 VS Code dark theme | ✅ |
| ⌨️ Keyboard shortcuts | ✅ |
| 🔢 Line numbers | ✅ |
| 🔄 Auto-indent | ✅ |
| 🔗 Auto-closing brackets | ✅ |
| 💬 Toggle comments | ✅ |

---

## 🚀 Quick Start

### Step 1 — Download and unzip

Download vs-code-python.zip and extract it to any folder on your computer.

### Step 2 — Install dependencies

Open a terminal inside the project folder and run:


cd path/to/vs-code-python
pip install -r requirements.txt
Step 3 — Launch the editor
 

python app/main.py
Done! The editor is running! 🎉

📖 Detailed Guide
Windows (PowerShell or CMD)
 

cd C:\Users\YourName\Downloads\vs-code-python
pip install -r requirements.txt
python app/main.py
Linux / macOS
 

cd ~/Downloads/vs-code-python
pip3 install -r requirements.txt
python3 app/main.py
Troubleshooting
"python is not recognized"

 

python3 app/main.py
"No module named app"
Make sure you are in the root project folder, not inside app/:

 

cd C:\Users\YourName\Downloads\vs-code-python
dir
# You should see: app/  resources/  requirements.txt  README.md
python app/main.py
⌨️ Keyboard Shortcuts
Shortcut	Action
Ctrl+N	📄 New file
Ctrl+O	📂 Open file
Ctrl+S	💾 Save
Ctrl+Shift+S	💾 Save as
Ctrl+F	🔍 Find
Ctrl+/	💬 Toggle comment
Ctrl+D	📋 Duplicate line
Ctrl+`	💻 Toggle terminal
F5	▶️ Run Python file
Ctrl+Shift+P	🎯 Command palette
Ctrl+Shift+E	📂 Show explorer
Ctrl+Shift+F	🔍 Search in files
Tab	➡️ Indent
Shift+Tab	⬅️ Unindent
📁 Project Structure
text

vs-code-python/
├── app/
│   ├── __init__.py        # Package init
│   ├── main.py            # 🚀 Main window (RUN THIS FILE)
│   ├── editor.py          # 📝 Code editor
│   ├── file_explorer.py   # 📂 File explorer
│   ├── terminal.py        # 💻 Terminal
│   ├── tabs.py            # 📑 Tab system
│   ├── menu_bar.py        # 📋 Menu bar
│   ├── status_bar.py      # 📊 Status bar
│   ├── sidebar.py         # 📌 Activity bar
│   ├── search.py          # 🔍 Search
│   ├── minimap.py         # 🗺️ Minimap
│   ├── welcome.py         # 🏠 Welcome page
│   ├── theme.py           # 🎨 Dark theme
│   └── syntax.py          # 🖍️ Syntax highlighting
├── resources/
│   └── config.json        # ⚙️ Settings
├── requirements.txt       # 📦 Dependencies
├── LICENSE                # 📜 MIT License
└── README.md              # 📖 This file
🛠️ Technologies
Python 3.8+ — programming language
Tkinter — GUI framework (built into Python)
Pygments — syntax highlighting engine
📦 Build to .exe (optional)
 

pip install pyinstaller
pyinstaller --onefile --windowed --name "VS Code for Python" app/main.py
The compiled .exe file will appear in the dist/ folder.

❓ FAQ
Q: Do I need internet?
A: No. The editor works completely offline.

Q: What Python version is required?
A: Python 3.8 or newer.

Q: Can I edit any file type?
A: Yes — Python, JavaScript, HTML, CSS, JSON, Markdown, plain text and more.

Q: How do I update?
A: Download the new version and replace the files.

📝 TL;DR
 

pip install -r requirements.txt
python app/main.py

# 📄 `LICENSE`
MIT License

Copyright (c) 2025 VS Code for Python

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

🇷🇺 Русский
✨ Возможности
Функция	Статус
📝 Редактор кода с подсветкой синтаксиса	✅
📂 Проводник файлов с деревом папок	✅
📑 Система вкладок	✅
💻 Встроенный терминал	✅
🔍 Поиск по файлам	✅
🗺️ Мини-карта кода	✅
📋 Верхнее меню	✅
📊 Статус бар	✅
📌 Панель активности	✅
🏠 Стартовая страница	✅
🎨 Тёмная тема VS Code	✅
⌨️ Горячие клавиши	✅
🔢 Номера строк	✅
🔄 Автоотступ	✅
🔗 Автозакрытие скобок	✅
💬 Комментирование кода	✅
🚀 Быстрый старт
Шаг 1 — Скачай и распакуй
Скачай vs-code-python.zip и распакуй в любую папку на компьютере.

Шаг 2 — Установи зависимости
Открой терминал (CMD или PowerShell) в папке проекта:

 

cd путь/к/vs-code-python
pip install -r requirements.txt
Шаг 3 — Запусти! 🚀
 

python app/main.py
Готово! Редактор запущен! 🎉

📖 Подробный гайд
Windows (PowerShell или CMD)
 

cd C:\Users\ВашеИмя\Downloads\vs-code-python
pip install -r requirements.txt
python app/main.py
Решение проблем
Ошибка "python не найден"

 

python3 app/main.py
Ошибка "No module named app"
Убедитесь что вы в корневой папке проекта, а не внутри app/:

 

cd C:\Users\ВашеИмя\Downloads\vs-code-python
dir
# Должны видеть: app/  resources/  requirements.txt  README.md
python app/main.py
⌨️ Горячие клавиши
Клавиши	Действие
Ctrl+N	📄 Новый файл
Ctrl+O	📂 Открыть файл
Ctrl+S	💾 Сохранить
Ctrl+Shift+S	💾 Сохранить как
Ctrl+F	🔍 Поиск
Ctrl+/	💬 Комментировать строку
Ctrl+D	📋 Дублировать строку
Ctrl+`	💻 Открыть/закрыть терминал
F5	▶️ Запустить Python файл
Ctrl+Shift+P	🎯 Палитра команд
Ctrl+Shift+E	📂 Показать проводник
Ctrl+Shift+F	🔍 Поиск в файлах
Tab	➡️ Добавить отступ
Shift+Tab	⬅️ Убрать отступ
📁 Структура проекта
text

vs-code-python/
├── app/
│   ├── __init__.py        # Инициализация пакета
│   ├── main.py            # 🚀 Главное окно (ЗАПУСКАЙ ЭТОТ ФАЙЛ)
│   ├── editor.py          # 📝 Редактор кода
│   ├── file_explorer.py   # 📂 Проводник файлов
│   ├── terminal.py        # 💻 Терминал
│   ├── tabs.py            # 📑 Вкладки
│   ├── menu_bar.py        # 📋 Верхнее меню
│   ├── status_bar.py      # 📊 Статус бар
│   ├── sidebar.py         # 📌 Панель активности
│   ├── search.py          # 🔍 Поиск
│   ├── minimap.py         # 🗺️ Мини-карта
│   ├── welcome.py         # 🏠 Стартовая страница
│   ├── theme.py           # 🎨 Тёмная тема
│   └── syntax.py          # 🖍️ Подсветка синтаксиса
├── resources/
│   └── config.json        # ⚙️ Настройки
├── requirements.txt       # 📦 Зависимости
├── LICENSE                # 📜 Лицензия MIT
└── README.md              # 📖 Этот файл
🛠️ Технологии
Python 3.8+ — язык программирования
Tkinter — GUI фреймворк (встроен в Python)
Pygments — подсветка синтаксиса
📦 Сборка в .exe (по желанию)
 

pip install pyinstaller
pyinstaller --onefile --windowed --name "VS Code for Python" app/main.py
Готовый .exe файл появится в папке dist/

❓ Частые вопросы
В: Нужен ли интернет?
О: Нет. Редактор работает полностью без интернета.

В: Какая версия Python нужна?
О: Python 3.8 или новее.

В: Можно ли открывать любые файлы?
О: Да — Python, JavaScript, HTML, CSS, JSON, Markdown, текстовые и другие.

В: Как обновить?
О: Скачайте новую версию и замените файлы.

📝 Коротко
 

pip install -r requirements.txt
python app/main.py
Made with ❤️ and 🐍

 

# 📄 `LICENSE`
MIT License

Copyright (c) 2025 VS Code for Python

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
