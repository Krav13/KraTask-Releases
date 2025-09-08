# 🚀 Инструкция по публикации KraTask

## ✅ Готовые файлы для пользователей:

- `README.md` - документация для пользователей
- `LICENSE` - MIT лицензия
- `KraTask-v1.1.zip` - готовое приложение (2.1 MB)
- `kratask_logo1024.png` - логотип приложения
- `kratask_logo.svg` - векторный логотип
- `screenshots/` - папка для скриншотов

## 🌐 Создание публичного репозитория:

### 1. Создайте новый репозиторий на GitHub:

1. Перейдите на https://github.com/new
2. **Repository name**: `KraTask-Releases` (или любое другое название)
3. **Description**: `KraTask - Modern Kanban Board for macOS (Releases Only)`
4. **Выберите**: "Public"
5. **НЕ ставьте галочки** на инициализацию
6. **Нажмите**: "Create repository"

### 2. Подключите локальный репозиторий:

```bash
# В папке KraTask-UserFiles выполните:
git remote add origin https://github.com/Krav13/KraTask-Releases.git
git branch -M main
git push -u origin main
git push origin v1.1.0
```

### 3. Создайте релиз на GitHub:

1. Перейдите в созданный репозиторий
2. Нажмите **"Releases"** → **"Create a new release"**
3. Выберите тег **"v1.1.0"**
4. Заголовок: **"KraTask v1.1.0 - First Release"**
5. Прикрепите файл **`KraTask-v1.1.zip`**
6. Нажмите **"Publish release"**

## 📝 Обновление ссылок:

Перед публикацией замените в `README.md`:
- `your_telegram_username` → ваш реальный Telegram
- `your_channel_username` → ваш реальный канал

## 🎯 Результат:

- **🔒 Приватный**: `Krav13/KraTask` - исходный код (только для вас)
- **🌐 Публичный**: `Krav13/KraTask-Releases` - релизы для пользователей

## 📱 Что увидят пользователи:

- ✅ Готовое приложение для скачивания
- ✅ Простой README с инструкциями
- ✅ Ссылки на поддержку
- ❌ НЕ увидят исходный код
