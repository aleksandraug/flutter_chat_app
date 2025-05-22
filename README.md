# Chat App

Flutter-приложение: чат с Firebase Authentication и потоками сообщений Firestore.

---

## 🚀 Особенности

- Регистрация и вход через Email/Password (Firebase Auth)
- Авторизация: хранение сессии, выход
- Отображение списка сообщений в реальном времени (Firestore «streams»)
- Загрузка и хранение фотографий  (Firebase Storage)
- Адаптивная тема: светлая/тёмная

---

## 🛠 Технологии

- **Firebase**  
  - Authentication  
  - Cloud Firestore (реализован поток сообщений через `.snapshots()`)  
  - Storage
- **State Management:** flutter_riverpod  
- **UI:** стандартные Material/Cupertino виджеты  

---

## ⚙ Установка и запуск

1. Клонировать репозиторий:
   ```bash
   git clone https://github.com/USERNAME/chat_app.git
   cd chat_app

2. Установить зависимости:
   flutter pub get


3. Запустить:
   flutter run

