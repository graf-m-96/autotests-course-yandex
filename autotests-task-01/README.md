forked from [urfu-2017/autotests-task-01](https://github.com/urfu-2017/autotests-task-01)

# "Покер на костях" [![Build Status](https://travis-ci.org/urfu-2017/autotests-task-01.svg?branch=master)](https://travis-ci.org/urfu-2017/autotests-task-01)

«Все, что происходит в Вегасе — остается в Вегасе»

... кроме удовольствия, которое
Джек получает, когда играет в покер. Карточная версия этой игры
кажется ему слишком сложной и скучной. Он ещё не научился
распознавать блеф, а партии по 20 минут сводят его с ума.

Кости - другое дело! Пять кубиков и только один бросок
на то чтобы понять, улыбнется ли Джеку удача.
Возможны следующие комбинации, в порядке убывания:
  * Покер 1️⃣1️⃣1️⃣1️⃣1️⃣ — пять костей одного вида
  * Каре 1️⃣1️⃣1️⃣1️⃣2️⃣ — четыре кости одного вида
  * Фулл хаус 1️⃣1️⃣1️⃣2️⃣2️⃣ — три кости одного вида + пара
  * Тройка 1️⃣1️⃣1️⃣2️⃣3️⃣ — три кости одного вида
  * Две пары 1️⃣1️⃣2️⃣2️⃣3️⃣ — две кости одного вида и две кости другого вида
  * Пара 1️⃣1️⃣2️⃣3️⃣4️⃣ — две кости одного вида
  * Наивысшее очко 1️⃣2️⃣3️⃣4️⃣5️⃣ — во всех остальных случаях

Реализуй функцию, которая принимает на вход массив чисел,
например `[1, 6, 3, 4, 6]` и возвращает название самой сильной
комбинации. В нашем примере это `Пара`.

### Чтобы решить задачу
  1. Создай форк репозитория. Нужно кликнуть по кнопке "Fork" в правом верхнем углу.
  2. Склонируй код к себе на ноутбук. `git clone https://github.com/<LOGIN>/autotests-task-01.git`, вместо `<LOGIN>` подставь логин на гитхабе.
  3. Установи зависимости `npm install`. Если команды `npm` ещё нет, установи [node.js](https://nodejs.org/en/download/)
  4. Напиши свой замечательный код в файле `lib/getPokerHand.js`.
     Покрой его тестами в `tests/getPokerHand-test.js`.
  5. Команда `npm test` запустит тесты.
  6. Зафиксируй изменения в git:
```[bash]
# Добавляем все файлы, которые изменились
git add lib/getPokerHand.js
git add tests/getPokerHand-test.js

# Фиксируем изменения
git commit -m 'Реализовал определение комбинаций'

# Отправляем в удаленный репозиторий
git push origin master
```
  7. Создай пулреквест. В описании укажи свою фамилию и имя.
  Чтобы посмотреть [покрытие кода](https://cloud.githubusercontent.com/assets/1654243/25126101/870aedd8-244a-11e7-89fe-eb392aae7835.png)
  или узнать причину поломки сборки нажми на ссылку [Details](https://cloud.githubusercontent.com/assets/1654243/25125909/e70bb254-2449-11e7-9ef0-ae062fd6b688.png)

### Почитать
  * [Слайды лекции автотесты](#https://github.com/urfu-2017/testing-slides)
  * [Как отправить пуллреквест](https://urfu-2016.github.io/javascript-slides/01-intro/#/37)

![](https://cloud.githubusercontent.com/assets/1654243/25169630/1e67721c-2501-11e7-8bf1-05f81bdced55.jpg)
