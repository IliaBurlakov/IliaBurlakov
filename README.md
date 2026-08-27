<h1 align="center">Привет, я Илья 👋</h1>

<h3 align="center">Java Backend Developer · студент ФИТ НГУ</h3>

<p align="center">
Разрабатываю backend-приложения на Java и Spring Boot.<br>
Интересуюсь проектированием backend-систем, реляционными БД, транзакциями и надежной интеграцией с внешними API.
</p>

---

### 👨‍💻 Обо мне

* 🎓 Студент 4 курса **ФИТ НГУ**
* ☕ Основной фокус — **Java Backend**
* 🧩 Работаю с **Spring Boot, PostgreSQL, REST API и Docker**
* 🏗️ Интересуюсь backend-архитектурой, транзакциями, concurrency и reliability
* 💼 Открыт к **стажировкам и Junior Java Backend позициям**
* 📡 Сейчас готовлю к публичной публикации свой основной pet-project — **PriceRadar**

---

### 🚀 Основной проект

#### 📡 PriceRadar

**Telegram-бот и backend-сервис для мониторинга цен Wildberries.**

Пользователь добавляет товар, выбирает регион и условие отслеживания, после чего PriceRadar периодически проверяет цену и уведомляет о достижении заданной цены или появлении нового минимума.

**Основной стек**

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square\&logo=springboot\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square\&logo=hibernate\&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square\&logo=flyway\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square\&logo=junit5\&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-3E8EDE?style=flat-square\&logo=testcontainers\&logoColor=white)

**Что интересного внутри:**

* 🧱 **Modular monolith** с разделением на `domain`, `application` и `infrastructure`
* 🎯 Разделение **WatchTarget** и **Subscription** — одна физическая проверка товара может использоваться несколькими подписками
* ⏱️ Scheduler проверяет только targets, для которых наступил `next_check_at`, после чего snapshot обрабатывается всеми связанными subscriptions
* 📨 **Transactional Outbox** отделяет бизнес-транзакцию от доставки уведомления в Telegram
* 🔁 **At-least-once delivery**, retry и idempotency для обработки временных и неоднозначных сетевых ошибок
* 🔒 Защита от stale/out-of-order данных и конкурентных изменений
* 🤖 Интеграция с **Telegram Bot API** через Java `HttpClient` и long polling без Telegram SDK
* 🛒 Импорт товаров из shared basket Wildberries через изолированный infrastructure adapter
* 📊 Хранение price snapshots и построение статистики по истории текущего отслеживания

> Репозиторий пока приватный. После финального security-аудита и feature freeze он будет опубликован здесь.

---

### 🛠️ Технологический стек

#### Backend

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square\&logo=springboot\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square\&logo=hibernate\&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square\&logo=flyway\&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square\&logo=junit5\&logoColor=white)

#### Infrastructure & Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square\&logo=gnubash\&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square\&logo=nginx\&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square\&logo=grafana\&logoColor=white)

#### ML / Data

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square\&logo=numpy\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square\&logo=pandas\&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square\&logo=scikitlearn\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square\&logo=pytorch\&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square\&logo=tensorflow\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square\&logo=jupyter\&logoColor=white)

---

### 📂 Другие проекты

#### RestStock Backend

Backend-часть учебного fullstack-проекта.

[![Repository](https://img.shields.io/badge/GitHub-reststock--back-181717?style=flat-square\&logo=github)](https://github.com/IliaBurlakov/reststock-back)

---

### 🌐 Связь со мной

[![Telegram](https://img.shields.io/badge/Telegram-@iliaburlakov23-26A5E4?style=flat-square\&logo=telegram\&logoColor=white)](https://t.me/iliaburlakov23)
[![Gmail](https://img.shields.io/badge/Gmail-iliaburlakov23-EA4335?style=flat-square\&logo=gmail\&logoColor=white)](mailto:iliaburlakov23@gmail.com)
[![VK](https://img.shields.io/badge/VK-Илья_Бурлаков-0077FF?style=flat-square\&logo=vk\&logoColor=white)](https://vk.ru/id534837260)
