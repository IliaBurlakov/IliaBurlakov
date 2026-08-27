<h1 align="center">Илья Бурлаков</h1>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Java+Backend+Developer;Spring+%E2%80%A2+PostgreSQL+%E2%80%A2+Docker;NSU+FIT+Student"
    alt="Typing SVG"
  />
</p>

---

### 👨‍💻 Обо мне

* 🎓 Студент 4 курса **НГУ ФИТ**, направление — **"Программная инженерия и компьютерные науки"**
* ☕ Основной фокус — **Java Backend:** Java, Spring Boot, PostgreSQL, REST API, Docker
* 🏦 **Лаборант СберЛаб НГУ**; дважды участвовал в летней школе (2025, 2026), где работал в команде над production проектом
* 💼 Открыт к **стажировкам и Junior Java Backend позициям**

---

### 🚀 Основной проект

#### 📡 [Price Radar](https://github.com/IliaBurlakov/price-radar)

**Backend-сервис для мониторинга цен на маркетплейсах.**

Сейчас Price Radar работает с **Wildberries**. Пользователь добавляет товар, выбирает регион и условие отслеживания, после чего сервис периодически проверяет цену и уведомляет о достижении заданного значения или появлении новой минимальной цены за период отслеживания.

Взаимодействие с пользователем построено через **Telegram-бота**.

**Основной стек**

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square\&logo=springboot\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square\&logo=hibernate\&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square\&logo=flyway\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square\&logo=junit5\&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-3E8EDE?style=flat-square\&logo=testcontainers\&logoColor=white)

**Главное о проекте:**

* 🎯 **Одна проверка цены может обслуживать множество пользователей.** Если несколько человек отслеживают один и тот же товар в одинаковом ценовом контексте, Price Radar не делает отдельный запрос к маркетплейсу для каждого пользователя
* 🧩 **Архитектура не привязана к конкретному маркетплейсу.** Для основной системы маркетплейс представлен через отдельный интерфейс, поэтому поддержку новых площадок можно добавлять отдельными интеграциями без переписывания бизнес-логики
* 🧱 Проект построен как **modular monolith**: предметные области разделены внутри одного приложения
* 🛡️ Система устойчива к **нестабильности внешних API и сети**: временные ошибки не приводят к потере важных уведомлений
* 📊 Price Radar хранит историю наблюдений, поэтому может показывать **минимальную цену, изменение стоимости и статистику за период отслеживания**
* 🌍 Цена отслеживается в рамках выбранного **региона**
* 🛒 Поддерживается **импорт товаров из корзины Wildberries**

[![Repository](https://img.shields.io/badge/GitHub-Посмотреть_проект-181717?style=flat-square&logo=github)](https://github.com/IliaBurlakov/price-radar)

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

#### 📦 [RestStock](https://github.com/IliaBurlakov/reststock-back)

**Система для управления складом ресторана**, разработанная в рамках дисциплины «Объектно-ориентированный анализ и дизайн».

В проекте реализованы учёт поставок и списаний, работа с партиями товаров и FIFO-списанием, управление блюдами и ингредиентами, заявки на закупку, ролевой доступ и журнал складских операций.

`Java 21` · `Spring Boot` · `Spring Security` · `Spring Data JPA` · `MySQL` · `React` · `Docker`

[![Backend](https://img.shields.io/badge/GitHub-Backend-181717?style=flat-square\&logo=github)](https://github.com/IliaBurlakov/reststock-back)
[![Frontend](https://img.shields.io/badge/GitHub-Frontend-181717?style=flat-square\&logo=github)](https://github.com/IliaBurlakov/reststock-front)

---

### 🌐 Связь со мной

<p align="left">
  <a href="https://t.me/iliaburlakov23">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/>
  </a>
  <a href="https://vk.ru/id534837260">
    <img src="https://img.shields.io/badge/VK-0077FF?style=for-the-badge&logo=vk&logoColor=white" alt="VK"/>
  </a>
  <a href="mailto:iliaburlakov23@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</p>
