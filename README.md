**Задание 1.**

Установить пакет @nestjs/mongoose и создать соединение с БД в App модуле приложения.

**Задание 2.**

Определить Mongoose-схему и сконфигурировать атрибуты схемы с использованием декораторов, поставляемых пакетом @nestjs/mongoose.

**Задание 3.**

Импортировать в собственный модуль Mongoose-модуль с необходимыми для работы схемами в рамках текущего модуля, объявить модель для работы с БД в конструкторе собственного сервиса.

**Задание 4.**

Создать контроллер с 4 методами для операций Get, Post, Put, Delete. По каждому маршруту в сервисе необходимо реализовать соответствующую запросу операцию с использованием модели для работы с БД, созданной на прошлых этапах.

:white_check_mark:

Запуск решения
```Batchfile
docker compose -f docker-compose.dev.yml up
```

Остановка и очистка контейнеров
```Batchfile
docker compose -f docker-compose.dev.yml down
```