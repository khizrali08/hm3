# hm3
# Сборка образа
`
docker build -t hizrali/nginx:0.1 .
`
# Авторизуемся в Docker
`
docker login
`
# Опубликуем образ
`bash
docker push hizrali/nginx:0.1
`
# Запускаем образ
`
docker run -d -p 8080:80 hizrali/nginx:0.1
`
# Ссылка на опубликованный образ в docker hub
`
https://hub.docker.com/r/hizrali/nginx
`
