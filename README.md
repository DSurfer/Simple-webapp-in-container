# Что это за приложение?
Это простое веб-приложение, обернутое в контейнер с помощью Docker`а.
### Образы, используемые для создания контейнера
`nginx:latest`, `surfera/workaimage:prac` - собранный образ приложения.
### Команда для того, чтобы скачать образ
`docker pull surfera/workimage:prac`
## Использование
Благодаря созданному Makefile, можно легко управлять приложением, используя следующие команды с помощью утилиты make:
`make build`, `make up`, `make restart`, `make pause`, `make stop`, `make unpause`, `make start`, `make rm`.
Работоспособность веб-приложения можно проверить по [адресу](http://127.0.0.1)
