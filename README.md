# diploma
```
agrobus/
├── backend/           # Spring Boot API
│   ├── src/main/java/com/agrobus/...
│   ├── resources/
│   └── Dockerfile
├── frontend/          # React интерфей
    ├── public/                  # Статичные ресурсы (favicon, index.html и пр.)
    ├── src/                     # Исходный код React-приложения
    │   ├── assets/              # Изображения, иконки, стили
    │   ├── components/          # Повторно используемые компоненты
    │   ├── pages/               # Отдельные страницы (Home, Login, Profile и т.д.)
    │   ├── services/            # API-запросы (например, axios-инстанс)
    │   ├── store/               # Redux или Zustand (если используется)
    │   ├── hooks/               # Кастомные хуки
    │   ├── App.jsx              # Главный компонент
    │   ├── index.js             # Точка входа в приложение
    │   └── routes.jsx           # Конфигурация маршрутов (React Router)
    ├── .env                     # Переменные окружения
    ├── package.json             # Зависимости проекта
    └── tailwind.config.js       # Конфигурация Tailwind (если используется)
├── docs/              # Диаграммы, схемы, архитектура
└── docker-compose.yml
```

```
## 🚀 Возможности

- 📢 Публикация объявлений на продажу скота
- 📍 Поиск и бронирование транспорта
- 💬 Онлайн-консультации с агроэкспертами
- 📅 Календарь агрособытий и напоминания
- 🔐 Авторизация пользователей и управление ролями
- 📊 Панель аналитики
- 📱 Поддержка мобильных устройств



## 🧱 Технологии

### Backend (Java)
- Java 17+
- Spring Boot (MVC, Security, Data JPA)
- PostgreSQL / MongoDB
- REST API + Swagger
- JWT для авторизации
- Lombok, MapStruct, Flyway

### Frontend
- React.js (или React Native для mobile)
- Axios / Redux / TailwindCSS

### DevOps
- Docker, Docker Compose
- GitHub Actions (CI/CD)
- AWS / Railway / DigitalOcean (деплой)

---


