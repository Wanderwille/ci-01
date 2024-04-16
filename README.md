# Домашнее задание к занятию 7 «Жизненный цикл ПО» - Подус Сергей

Необходимо создать собственные workflow для двух типов задач: bug и остальные типы задач. Задачи типа bug должны проходить жизненный цикл:

1. Open -> On reproduce.
2. On reproduce -> Open, Done reproduce.
3. Done reproduce -> On fix.
4. On fix -> On reproduce, Done fix.
5. Done fix -> On test.
6. On test -> On fix, Done.
7. Done -> Closed, Open.

Остальные задачи должны проходить по упрощённому workflow:

1. Open -> On develop.
2. On develop -> Open, Done develop.
3. Done develop -> On test.
4. On test -> On develop, Done.
5. Done -> Closed, Open.

**Что нужно сделать**

1. Создайте задачу с типом bug, попытайтесь провести его по всему workflow до Done. 
1. Создайте задачу с типом epic, к ней привяжите несколько задач с типом task, проведите их по всему workflow до Done. 
1. При проведении обеих задач по статусам используйте kanban. 
1. Верните задачи в статус Open.
1. Перейдите в Scrum, запланируйте новый спринт, состоящий из задач эпика и одного бага, стартуйте спринт, проведите задачи до состояния Closed. Закройте спринт.
2. Если всё отработалось в рамках ожидания — выгрузите схемы workflow для импорта в XML. Файлы с workflow и скриншоты workflow приложите к решению задания.


## Ответ:

Workflow Bug

![Скриншот 1](https://github.com/Wanderwille/scrinshot/blob/main/bug%20workflows.png)

Файл hml: https://github.com/Wanderwille/file/blob/main/BUG%20(2).xml

Workflow Other

![Скриншот 2](https://github.com/Wanderwille/scrinshot/blob/main/other%20workflow.png)

Файл hml: https://github.com/Wanderwille/file/blob/main/Other.xml

1. Задача Bug:

![Скриншот 3](https://github.com/Wanderwille/scrinshot/blob/main/закрыта%20задача%20bug.png)


2. Задача Epic:

![Скриншот 5](https://github.com/Wanderwille/scrinshot/blob/main/задачи%20типа%20Epic.png)

![Скриншот 6](https://github.com/Wanderwille/scrinshot/blob/main/epicDone.png)

3. Scrum:

![Скриншот 7](https://github.com/Wanderwille/scrinshot/blob/main/sptint.png)

4. Спринт:

![Скриншот 8](https://github.com/Wanderwille/scrinshot/blob/main/sprint2.png)

