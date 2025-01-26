# WG-MTRIX

WG-MTRIX - это легковесная панель для управления WireGuard VPN.

## Установка

1. Склонируйте репозиторий:
   ```bash
   git clone <ваш_репозиторий>
   cd wg-mtrix
   ```

2. Соберите Docker-образ:
   ```bash
   docker build -t wg-mtrix .
   ```

3. Запустите контейнер:
   ```bash
   docker run -d -p 5000:5000 --name wg-mtrix wg-mtrix
   ```

4. Откройте веб-браузер и перейдите по адресу `http://<ваш_сервер>:5000`.

## Особенности

- Простая установка и настройка.
- API для управления WireGuard.

## Лицензия

MIT License