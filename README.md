Предварительно должен быть скачен и запущен Docker. Скачаны образы для докера Node.js, mysql, postgresql.
1. Выполнить в терминале команду `docker-compose up`
1. Открыть новую консоль.
1. Выполнить в терминале команду
   `java -jar artifacts/aqa-shop.jar`
1. С помощью команды ./gradlew test
2. Запустить команду для генерации отчетов gradlew allureServe

