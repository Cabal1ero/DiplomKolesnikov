# Интернет-магазин компьютерной техники

Проект интернет-магазина компьютерной техники, состоящий из двух частей:
- Backend (Django + Django Ninja)
- Frontend (Next.js)

## Структура проекта

```
├── backend/           # Django backend
└── frontend/         # Next.js frontend
```

## Установка и запуск

### Backend

1. Создайте виртуальное окружение:
```bash
python -m venv venv
source venv/bin/activate  # для Linux/Mac
venv\Scripts\activate     # для Windows
```

2. Установите зависимости:
```bash
cd backend
pip install -r requirements.txt
```

3. Запустите сервер:
```bash
python manage.py runserver
```

### Frontend

1. Установите зависимости:
```bash
cd frontend
npm install
```

2. Запустите сервер разработки:
```bash
npm run dev
```

## Ветки

- `main` - основная ветка
- `backend` - ветка для backend разработки
- `frontend` - ветка для frontend разработки 