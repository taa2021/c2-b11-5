# C2.B11.5 Практическое задание 11.5


## Задание

Оригинальная формулировка задания приведена [здесь](./TASK.md).

## Примечания к решению

- Код "простейшего запроса" - исправлен

## Ход решения (принципиальная схема развертывания)

1. Устанавливаем CI: [1](https://concourse-ci.org/install.html), [2](https://github.com/concourse/concourse-docker)

2. Настраиваем [pipeline](./project.yml)

3. Несколько раз меняем [скрипт запроса данных](./data.sql), фиксируем результаты работы CI-инструементария

## Выводы по решению

- CI/CD - развернут
- По изменению скрипта запроса данных pipeline - отрабатывает, результаты - выводятся
- Выводы скриптов (после отладки, сработка - автоматически, по изменению репозитория):
  - [первый (билд 2)](./out-screen--build2.png)
  - [второй (билд 3)](./out-screen--build3.png)
