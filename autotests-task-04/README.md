forked from [urfu-2017/autotests-task-04](https://github.com/urfu-2017/autotests-task-04)

# Задача «Кто я?»

## Условие
Есть 7 веб-мессенджеров:

* https://team1-kilogram.now.sh
* https://kilogram-team2.now.sh
* https://team3.now.sh
* https://k1logram.now.sh
* https://the-best-messenger.now.sh
* https://k1logram-team6.now.sh
* https://team7chat.now.sh/

#### Задача:
Написать e2e-тест на следующий тестовый сценарий

#### Тестовый сценарий:
1. Войти с помощью github-аккаунта в любой из семи чатов
2. Зайти в свой профиль в чате
3. Сравнить, что информация со страницы "Профиль" чата совпадает с информацией пользователя на Github

#### Важно:
1. Тест должен ходить в облачный Selenium Grid
1. Вместе с пулл реквестом нужно прикрепить ссылку на видео прохождения теста
1. Нельзя выбрать тот чат, в котором ты являешься разработчиком
1. На видео должно быть видно, что используется твой github-аккаунт

## Установка и запуск
#### Установка:
1. Установить [JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk10-downloads-4416644.html)
2. Установить зависимости
```
npm install
```

#### Запуск с тестовым пользователем:
1. Получаем Username и Access-Key аккаунта облачного selenium grid
2. Запускаем команду с переменными окружения
```
// в примере тестовый аккаунт гитхаба

USERNAME=<подставь> ACCESSKEY=<подставь> GH_LOGIN=sel-lesson GH_PWD=4vN8VopAYD13lL5 npm test
```