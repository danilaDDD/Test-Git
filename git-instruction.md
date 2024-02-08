# Инструкция по работе с Git
## Lesson 1
1. git init - создание репозитория
2. git add - добавить версионость
3. git commit -m "Комментарий" - создание commit
> git commit -am "Комментарий" - git add и git commit -m "Комментарий"

[Конспект 1](https://habr.com/ru/articles/541258/ "Конспект 1")

git status - вызвать блок информации по состоянию репозитория

## Lesson 2
+ git branch - проверить все ветки
+ git checkout название ветки - переход на ветку
+ git branch Название - создание ветки
+ git branch -b название ветки - создание ветки и переход на нее
+ git merge название- сохранение с одной ветки (название) на действующую
+ git log —graph - просмотр изменений по веткам
> Конфликт:
4 команды -> git add -> git commit -m

## Lesson 3
### Прикрепление к удаленному репозиторию:
1. git remote add origin https://github.com/namdykova/Test-Git.git
2. git branch -M main
3. git push -u origin main

+ git pull - сохранение на локальний файл удаленного репозитория
+ git push —u origin main отправление на удаленный репозиторий

#### GitHub:
+ Создать репозиторий
+ Fork - для работы с чужим репозиторием - копия репозитория
+ В VS Code -> Clone Git Repository