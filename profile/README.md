# catalogue
Каталог ПО отдела


| Название          | Описание                         | Технологии          | Репозитории                                                      | Дата последнего обновления | Статус        | Версия  | Зависимости |
|-------------------|----------------------------------|---------------------|------------------------------------------------------------------|----------------------------|---------------|---------|-------------|
| sa-server         | Логгирующий сервер для полигона  | Python, PostgreSQL, docker, sockets, pyserial    | [sa-server](https://github.com/technomaticsDevTeam/sa-server)  | 2024-10-03                  | Активный (ведется рефакторинг и поддержка)     | 1.0.7   | <strong>Python 3.12</strong>: crcmod==1.7 psycopg2==2.9.9 pyserial==3.5 PyYAML==6.0.1 <strong>docker compose v3.8</strong> |
| sa-web-server     | Сервис умного полигона, работает совместно с sa-server  | Python, JavaScript, docker, FastAPI, React, sockets, jupyter_core    | [sa-web-server](https://github.com/technomaticsDevTeam/sa-web-server) , [sa-web-server-frontend](https://github.com/technomaticsDevTeam/sa-web-server-frontend) , [sa-web-server-manifest](https://github.com/technomaticsDevTeam/sa-web-server-manifest) | 2024-10-03                  | Активный (ведется рефакторинг и поддержка)     | 1.0.3   | <strong>Python 3.12</strong>, <strong>node.js 20 </strong>, <strong>docker compose v3.8</strong> |
