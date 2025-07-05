# Ростелеком — Система индивидуальных планов развития 

Веб-приложение для создания и управления индивидуальными планами развития сотрудников.  
**Производственная практика в компании Ростелеком**.

---

## 🛠 Технический стек
### Базовые настройки
- **Python**: 3.13.5  
- **Django**: 5.2.4  
- **Виртуальное окружение**: `djvenv` (изолированное с фиксированными зависимостями)

---

## 🚀 Быстрый старт
### 1. Инструкция клонирования и настройки веб-приложения
```bash
# 1. Клонировать репозиторий
git clone https://github.com/ret-hub123/rostel-individual-development-plans/blob/main/README.md
cd rostel-individual-development-plans

# 2. Создать и активировать виртуальное окружение
python -m venv djvenv

# Windows:
.\djvenv\Scripts\activate
# macOS/Linux:
source djvenv/bin/activate

# 3. Установить зависимости
pip install -r requirements.txt

# 4. Применить миграции
python manage.py migrate

# 5. Запустить сервер
python manage.py runserver
```
### Приложение будет доступно по адресу: http://127.0.0.1:8000
