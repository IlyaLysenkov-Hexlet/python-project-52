# Проект Менеджер задач

### Hexlet tests and linter status:

[![Actions Status](https://github.com/IlyaLysenkov-Hexlet/python-project-52/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/IlyaLysenkov-Hexlet/python-project-52/actions)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=IlyaLysenkov-Hexlet_python-project-522&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=IlyaLysenkov-Hexlet_python-project-522)
[![Maintainability](https://sonarcloud.io/api/project_badges/measure?project=IlyaLysenkov-Hexlet_python-project-522&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=IlyaLysenkov-Hexlet_python-project-522)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=IlyaLysenkov-Hexlet_python-project-522&metric=coverage)](https://sonarcloud.io/summary/new_code?id=IlyaLysenkov-Hexlet_python-project-522)

🔗 [Веб-версия приложения (Render)](https://python-project-52-02nk.onrender.com/)

---

## 📌 Описание

Менеджер задач — это приложение для организации и планирования задач с поддержкой многопользовательского доступа. Каждый пользователь может:

- Управлять своими задачами
- Назначать статусы и метки
- Редактировать и удалять задачи
- Управлять своим профилем (регистрация, редактирование, удаление)

Приложение поддерживает авторизацию, а также фильтрацию задач по различным параметрам.

---

## 🚀 Основные функции

- ✅ **Управление задачами**: создание, редактирование и удаление
- 👥 **Работа с пользователями**: регистрация, обновление, удаление
- 🏷️ **Метки**: добавление, редактирование, удаление
- 📊 **Статусы задач**: "новый", "в процессе", "завершён" и другие
- 🔍 **Фильтрация**: по статусу, меткам, автору и исполнителю

---

## 🛠️ Используемые технологии

- **Python** — основной язык
- **Django** — фреймворк для веб-разработки
- **Bootstrap 5** — стилизация интерфейса
- **Gunicorn + Render** — деплой
- **Django ORM** — работа с базой данных
- **Django i18n** — поддержка многоязычности

---

## 📦 Локальный запуск

### 1. Клонировать репозиторий

```bash
git clone https://github.com/IlyaLysenkov-Hexlet/python-project-52.git
cd python-project-52
```

### 2. Установить зависимости и собрать проект

```bash
make install
```
### 3. Настройка .env

```
Если запускаем проект локально, то нужно создать .env Файл, где требуется указать
SECRET_KEY=your-secret-key
DATABASE_URL=sqlite:///db.sqlite3
```

### 4. Запустить сервер

```bash
make start
```

### 5. Перейти в браузере по адресу

```
http://127.0.0.1:8000/
```

---

## 👤 Автор

- GitHub: [@IlyaLysenkov-Hexlet](https://github.com/IlyaLysenkov-Hexlet)
- Исходный код проекта: [python-project-52](https://github.com/IlyaLysenkov-Hexlet/python-project-52)

---

## 🔗 Полезные ссылки

- [Документация Django (RU)](https://docs.djangoproject.com/ru/)
- [Render](https://render.com)
- [SonarCloud — анализ кода](https://sonarcloud.io/summary/new_code?id=IlyaLysenkov-Hexlet_python-project-52)
