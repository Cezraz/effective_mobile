## Описание

Простое веб-приложение, развёрнутое в Docker:
nginx выступает в роли reverse proxy и проксирует запросы к backend-сервису.

## Запуск проекта

```bash
docker compose up -d --build
```
## Проверка
```bash
curl http://localhost
```
Если выводится "Hello from Effective Mobile!", значит сервис работает правильно!
