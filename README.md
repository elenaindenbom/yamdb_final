# yamdb_final
Проект для изучения работы GitHub Actions.
За основу взято приложение api_yamdb:
https://github.com/elenaindenbom/api_yamdb/blob/master/README.md

### В workflow описано четыре задачи:
- проверка кода на соответствие стандарту PEP8 (с помощью пакета flake8) и запуск pytest;
- сборка и доставка докер-образа для контейнера web на Docker Hub;
- автоматический деплой проекта на боевой сервер;
- отправка уведомления в Telegram о том, что процесс деплоя успешно завершился.

https://github.com/elenabom/infra_actions/actions/workflows/yamdb_workflow.yml/badge.svg
