# lopvv_microservices
lopvv microservices repository

## Homework-12
- Добавил .travis.yml для интеграции с Travis.
- Добавил шаблон для PR.
- Установил Docker CE.
- Познакомился с основными командами для взаимодействия с docker-daemon.



#### Задание со \*
Решение описано в docker-monolith/docker-1.log


## Homework-13
- Создал новый проект в GCP.
- Настроил локальное окружение на работу с новым пректом.
- Создал docker host с помощью docker machine на GCE.
- Создал образ на удаленном docker host.
- Познакомился с DockerHub.


#### Задание со \*
Вернуcь позже

## Homework-14
- Написали Dockerfile для трех сервисов.
- Познакомился с оптимизацией размера контейнеров.
- Запустили контейнеры и убедились в работе приложения.


#### Задание со \* (1)
Вернуcь позже
#### Задание со \* (2)
Вернуcь позже


## Homework-15
- Познакомился с работой сетей в docker
- Познакомился с работой docker-compose
- Собрал и запустил образо приложения используя docker-compose

Узнайте как образуется базовое имя проекта. Можно ли его задать? Если можно то как?

По умолчанию базовое имя зависит от имени папки, в которой находится проект. Его можно изменить одним из трех способов:
- задать переменную окружения COMPOSE_PROJECT_NAME
- использовать флаг -p, --project-name NAME
- переименовать папку с проектом

#### Задание со \*
Вернуcь позже

## Homework-16
- Познакомился с работой Prometheus
- Собрал образ с Prometheus для мониторинга сервисов приложения reddit
- Собрал и запушил образы в DockerHub https://hub.docker.com/r/randomile/
- Добавил Node Exporter в Prometheus для мониторинга состояния Docker хоста


#### Задание со \*
Вернуcь позже


## Homework-17
- Разделил docker-compose.yml на 2. В одном описание приложений (docker-compose.yml), во втором мониторинг (docker-compose-monitoring.yml)
- Собрал образ cAdvisor для наблюдения за состоянием контейнеров
- Добавил контейнер с Grafana для визуализации данных
- Разобрался с импортом/экспортом dashboards в grafana
- Создал 2 dashboard с несколькими графиками
- Познакомился с различными типами графиков и функций
- Собрал образ alertmanager с настройками интеграции со Slack
- Запушил образы в DockerHub https://hub.docker.com/r/randomile/

#### Задание со \*
Вернуcь позже


## Homework-18
- Пересобрал образы для работы с функционалом логирования
- Добавил отдельный файл для системы логирования (ELK а точнее EFK) docker-compose-logging.yml
- Пересобрал образ Fluentd с нужной конфигурацией
- Включил логирование для контейнеров post и ui
- Познакомился с интерфейсом Kibana
- Добавил фильтры для парсинга json логов и неструктурированных (с помощью регулярного выражения и grok шаблона)

#### Задание со \*
Вернуcь позже

## Homework-19
- Прошел туториал Kubernetes The Hard way
- Проверил, что дейплойменты написаны корретно и поды запускаются
