# Docker
1. Установка Docker 
   - установи докер https://docs.docker.com/engine/install/ubuntu/
   - добавь своего пользователя в группу docker (нужно будет выйти/зайти в терминал) 
   - убедись что команда docker ps отрабатывает без sudo.
2. Основные команды для работы с Docker 
   - Как спулить образ из docker hub к себе на комп (как посмотреть что он спулился)
   - Как развернуть из спуленного образа докер контейнер? 
   - Как его оставновить? 
   - Как посмотрть информацию о запущенном контейнере? (ip, volumes и тд)
   - Как запустить его в интерактивном режими или в виде демона/службы?
   - Как создать volume для него и как его удалить?
   - Как создать сеть между контейнерами?
   - Подним два контейнера с одним volume для двоих и в одной сети
3. Работа с Dockerfile
   - напиши dockerfile для запуска двух контейнеров, например для своего пет проекта или в интернете можно скачать любой (например с базой и вэб сервером)
   - собери два контейнера и запусти убедись что сервис тебе отвечает на localhost:8080
4. Работа с docker-compose
   - напиши docker-compose файл который поднимет другой проект состоящий
   - уже из 3х и более контейнеров.
   - Попробуй зайти в терминал каждого контейнера и посмотри как они работают
   - передай в контейнер через docker-compose и dockerfile переменные окружения. 
     - Результатом должно быть - когда заходишь через терминал в контейнер при вводе команды printenv можно найти среди списка переменных окружения твои переменные со значениями
5. Разработка и запуск проекта
   - возьми свой проект и с нуля напиши к нему dockerfile и docker-compose для сборки и развертывания всего проекта.