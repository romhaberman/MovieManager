# Домашнее задание к занятию "Композиция и зависимость объектов. Mockito при создании автотестов"

## Цель задания

1. Научиться проектировать классы, внутреннее состояние которых содержит наборы данных

------
## Задание 1 (обязательное)

В этой задаче не нужно разделять менеджер и репозиторий — все фильмы должны храниться внутри массива в поле самого менеджера. Изначально, сразу после создания, менеджер не должен содержать фильмов. 

Менеджер должен уметь выполнять следующие операции:
1. Добавление нового фильма.
2. Вывод всех фильмов в порядке добавления (`findAll`).
3. Вывод максимально лимит* штук последних добавленных фильмов в обратном от добавления порядке (`findLast`).