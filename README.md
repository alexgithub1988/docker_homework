1. Запустить DockerDekstop (Для Windows)
2. Запустить сборку контейнера docker build -t my_app .
3. Запустить контейнер docker run -d -p  8000:8000  my_app:latest 
4. Проверить что http://localhost:8000/ping  есть сообщение {"message":"pong"}