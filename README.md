# Affise Dashboard - Frontend

## ⚠️ ВАЖНО! Перед загрузкой на Netlify:

1. Откройте файл `login.html` в текстовом редакторе (Блокнот)
2. Найдите строку (примерно 80-я строка):
   ```javascript
   const API_URL = 'https://ваш-проект.railway.app';
   ```
3. Замените URL на реальный адрес вашего API с Railway
4. Сохраните файл

## 📁 Файлы:
- `index.html` - главная страница (редирект на login)
- `login.html` - страница входа
- `_redirects` - конфигурация для Netlify
- `dashboard.html` - добавьте ваш файл дашборда сюда

## 🔐 Тестовый аккаунт:
- Логин: `admin`
- Пароль: `admin123`

## 📤 Как загрузить на Netlify:
1. Откройте https://netlify.com
2. Нажмите "Add new site" → "Deploy manually"
3. Перетащите всю папку с файлами в окно браузера
4. Готово!
