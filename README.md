# 👋 Привет! Я Роман (Sokolpr / peanutsh)

**Backend-разработчик Java** · Учусь в Школе 21

📍 Челябинск, Россия · Открыт к переезду и удалённой работе  
📬 Telegram: [@soko1pr](https://t.me/soko1pr) · Email: [Peanutsh@yandex.ru](mailto:Peanutsh@yandex.ru)

---

## 🧰 Технологический стек

**Языки**  
Java · C · C++

**Фреймворки и библиотеки**  
Spring Boot · Spring Security · Spring Data JPA (Hibernate) · gRPC · JWT · Lombok · MapStruct · OpenAPI (Swagger) · WebSocket 

**Базы данных и очереди**  
PostgreSQL · Redis · Kafka · Flyway · Liquibase

**Инструменты и DevOps**  
Git · Docker · Docker Compose · CI/CD · Maven · Gradle · Linux · Make · JIRA

**Тестирование**  
JUnit · Mockito · Testcontainers · Integration Tests

## 🚀 Ключевые проекты

### [🛒 ShopAPI](https://github.com/Sokolpr/ShopAPI)  
RESTful API для интернет-магазина бытовой техники.  
- Реализована микросервисная архитектура с gRPC-авторизацией  
- Интеграция с PostgreSQL, Redis, Kafka  
- Документация OpenAPI (Swagger)  
- Контейнеризация через Docker Compose  

**🚧 В разработке (план развития):**
- Подключение **OAuth2 / Keycloak** для гибкой авторизации
- Хранение изображений товаров в **S3 (MinIO / AWS S3)**
- Микросервис **Периодическое обновление цен и остатков** с помощью **Spring Scheduler** (@Scheduled) с публикацией событий в Kafka
- **WebSocket / SSE** для отправки обновлений клиентам в реальном времени
- **Nginx** в качестве reverse-proxy и балансировщика


### [🎮 TicTacToe](https://github.com/Sokolpr/TicTacToe)  
Сервер пошаговой игры «Крестики-нолики».  
- Поддержка PvP и PvE (AI на основе алгоритма минимакса)  
- JWT-авторизация и хранение данных в PostgreSQL  
- REST API и WebSocket для реального времени  

### [🖥️ 3D Viewer](https://github.com/Sokolpr/3D-Viewer)  
Визуализатор каркасных 3D-моделей.  
- Загрузка OBJ-файлов  
- 3D-трансформации (поворот, масштабирование, перемещение)  
- Реализован на C++ с использованием Qt  

### [🧩 Brick Game](https://github.com/Sokolpr/BrickGame)  
Классические игры «Тетрис» и «Змейка» на C++.  
- Поддержка двух интерфейсов: терминальный (ncurses) и графический (Qt)  
- Игровая логика, управление и отрисовка в реальном времени  

---

