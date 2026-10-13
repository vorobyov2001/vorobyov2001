<h1 align="center">Привет, я Даниил 👋</h1>
<h3 align="center">Python Backend Developer · FastAPI · PostgreSQL · asyncio</h3>

<p align="center">
  <a href="https://t.me/vorobyod"><img src="https://img.shields.io/badge/Telegram-@vorobyod-26A5E4?style=flat&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:vorobyovd.2001@gmail.com"><img src="https://img.shields.io/badge/Email-vorobyovd.2001@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Алматы-UTC+5-555?style=flat" alt="Location">
  <img src="https://img.shields.io/badge/remote-only-2ea44f?style=flat" alt="Remote">
</p>

---

Backend-разработчик с опытом 3,5+ года. Работаю с высоконагруженными транзакционными системами в финтехе и iGaming. Специализируюсь на надёжности платёжных операций (идемпотентность, конкурентные списания), оптимизации SQL и интеграциях с внешними провайдерами и банковскими процессингами.

- 🎰 **Сейчас:** iGaming-платформа (Кипр, удалённо), ~25 тыс. DAU
- 💳 **Раньше:** Globerce Capital: Loggy, сервис доставки банковских карт (~30 тыс. доставок в месяц)
- 🌐 **Языки:** русский (родной), английский B1

## 🛠 Стек

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat&logo=gitlab&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)

## 📈 Что я делал

- ⚡ Ускорил эндпоинт истории транзакций в ~3 раза (300 → 100 мс): переписал SQL и добавил составной индекс
- 🔁 Убрал дубли платёжных транзакций: сделал идемпотентную обработку вебхуков провайдера, после этого не было ни одного дубля
- 🚀 Сократил прогон симуляции на 1 млн операций с 3–4 часов до 15 минут: asyncio и батчевая запись в БД
- 🗄 Снизил нагрузку на PostgreSQL примерно на треть, вынеся справочные данные в Redis
- 🔒 Сделал автоблокировку карт через банковский процессинг: 287 срабатываний, ни одного случая мошенничества
- ✅ Сократил ошибки передачи карт в 6 раз за счёт валидации по QR-коду

## 📂 Проекты

| Проект | Описание |
|---|---|
| [**payment_test_task**](https://github.com/vorobyov2001/payment_test_task) | Асинхронный процессинг платежей: Transactional Outbox, RabbitMQ (FastStream), повторы через TTL-очереди и DLQ, защита от двойного списания, webhook. Есть нагрузочный тест с проверкой инвариантов |
| [**TVPolls**](https://github.com/vorobyov2001/TVPolls) | Голосования в прямом ТВ-эфире: Redis как горячий путь записи, атомарная дедупликация, батч-синхронизация счётчиков в PostgreSQL, админка |

---

<p align="center"><i>Открыт к предложениям о работе на позицию Python Backend Developer (удалённо)</i></p>
