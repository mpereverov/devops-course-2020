# Задание:
Создать скрипт(project.sh) запускающий 3 контейнера:
1. запускает server.rb(руби файл, работает только с версией 2.6.0)
2. запускает postgres базу данных(версии 9.6.5)
3. запускает redis

Настроить доступ к базе через переменную окружения DB, доступ к редису через CACHE
Извне доступ должен быть только к вебсерверу руби через 9000 порт(сам руби открывает 4567)

Проверить можно через браузер или curl по следующим ссылкам: http://localhost:9000/, http://localhost:9000/db, http://localhost:9000/cache