### Документация =]

самый простой вывод текста в странице в браузере

Запуск
1. ```git clone git@github.com:vloneonme/tz-http-server.git``` 
2. ```cd tz-http-server```
3. ```docker compose up -d```

Проверить, что все работает
```curl localhost```

Технологии: Docker, Docker Compose, Python 3.12, Nginx 1.27-alpine.
Особенности реализации:

1. Backend запускается от non-root пользователя
2. Healthcheck'и
3. Все рекомендуемые proxy-заголовки
4. Отдельная Docker-сеть
5. Только порт 80 nginx проброшен на хост
6. Минимальный размер образов
   
