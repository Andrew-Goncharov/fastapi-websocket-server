# fastapi-websocket-server

Тестовое приложение для отправки сообщений через веб-сокеты.

Команда для запуска сервиса:

 - <code> uvicorn main:app --host 0.0.0.0 --port 80 </code>
 
 - <code> uvicorn main:app --host 0.0.0.0 --port 5000 --ssl-keyfile=./key.pem --ssl-certfile=./cert.pem
 </code>