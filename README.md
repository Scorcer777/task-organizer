# Описание
task-organizer - небольшой веб сервис для организации задач. Технически он представляет собой API на DRF работающий в связке с фронтэнд приложением на JSReact. Сервис позволяет ввети текст задачи и сохранить ее, а также позже отметить, как выполненную или удалить.

# Установка
Как запустить проект:
### 1. Клонировать репозиторий и перейти в него в командной строке:
```git bash
git clone https://github.com/Scorcer777/task-organizer/edit/
cd api_yamdb
```
### 2. Cоздать и активировать виртуальное окружение:
```bash
python3 -m venv env
source venv/Scripts/activate
```
### 3.Установить зависимости из файла requirements.txt:
```bash
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```
Выполнить миграции:
```bash
python3 manage.py migrate
```
Опциональлно можно также импортировать в базу данные, подготовленные для демонстрации работы API:
```bash
python3 manage.py import
```
### 4. Запустить проект:
```bash
python3 manage.py runserver
```
