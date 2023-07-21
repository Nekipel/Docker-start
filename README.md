Java Advanced . Лекция 1.1.4
Цель: практика использования Docker.

Задание: во время выполнения pre-project в твоем приложении использовалась одна из СУБД — PostgreSql / MySql.

Задача:

Найти образ СУБД на Docker Hub либо загуглить команду запуска и запустить контейнер с ней.

Запустить последнее приложение pre-project, используя СУБД, запущенную в Docker.

Подсказки: 

Чтобы приложение могло работать с базой данных, запущенной в Docker, необходимо выполнить проброс порта. Обрати внимание, что стандартные порты могут конфликтовать из-за уже установленной локально СУБД.

Cхему либо пользователя и его пароль можно инициализировать сразу при запуске контейнера.

Ты можешь работать с докером прямо в Intellij IDEA, используя терминал или встроенные tools.

Dockerfile:
https://www.youtube.com/watch?v=gir9Ay4pQU4&list=PLD5U-C5KK50XMCBkY0U-NLzglcRHzOwAg&index=6&ab_channel=DKA-DEVELOP
https://www.youtube.com/playlist?list=PLD5U-C5KK50XMCBkY0U-NLzglcRHzOwAg

https://www.youtube.com/watch?v=_uZQtRyF6Eg&ab_channel=BogdanStashchuk - лекция
https://dev.to/sandrogiacom/run-mysql-on-docker-and-use-in-your-java-app-jpn - статья

доп материалы
-https://vc.ru/dev/218052-effektivnoe-ispolzovanie-docker
-https://habr.com/ru/companies/southbridge/articles/713304/
-https://habr.com/ru/companies/ruvds/articles/450312/
