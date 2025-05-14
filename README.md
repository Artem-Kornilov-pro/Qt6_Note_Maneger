# 📝 Qt6 Note Manager

Простое десктопное приложение для управления заметками, созданное с использованием **PyQt6** и **SQLAlchemy**.

## 🚀 Возможности

- Создание, редактирование и удаление текстовых заметок
- Список заметок с отображением даты создания и обновления
- Поиск заметок по названию
- Сортировка по дате
- Поддержка светлой и тёмной тем
- Использование `QTableView` и `QAbstractTableModel` для отображения данных
- Архитектура с разделением логики и интерфейса
- Использование SQLite и SQLAlchemy

## 🖼 Интерфейс

![Screenshot](screenshots/main_window.png)

## 🛠️ Установка и запуск

```bash
# Клонируй репозиторий
git clone https://github.com/Artem-Kornilov-pro/Qt6_Note_Maneger.git
cd Qt6_Note_Maneger

# Установи зависимости
pip install -r requirements.txt

# Запуск приложения
python main.py
