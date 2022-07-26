# **Инструкция по работе с системой контроля версий Git**

![Логотип](git.jpg)

Общая информация про Гит

## Инициализация репозитория

Чтобы инициализировать репозиторий нужно ввести команду:

    git init

## Проверка состояния репозитория

Чтобы проверить статус нужного репозитория нужно ввести команду:

    git status

## Проверка версионности

 Чтобы проверить статус версионности нужно ввести команду:

    git version

## Фиксация изменений

Чтобы зафиксировать изменения нужно ввести команду:

    git commit -m "Описание изменений"

## Просмотр истории коммитов

Чтобы посмотреть историю коммитов нужно ввести команду:

    git log или git log --oneline

## Переключение между версиями

Чтобы переключиться на другую (раннее сохраненную) версию репозитория используется команда:

    git checkout

## Просмотр различий между коммитами

Для просмотра различий между разными версиями репозитория используется команда:

    git diff

## Ветвление в Git

Ветвление в гит позволяет им работать параллельно с разными задачами в одном репозитории

## Создание новой ветки

Чтобы создать новую ветку используется команда:

    git branch <имя_ветки>

## Слияние веток

Чтобы влить одну ветку в другую нужно находясь на той ветке **куда** вливаем выполнить команду:

    git merge <имя вливаемой ветки>

## Переключение между ветками

## Удаление веток
 
 Чтобы удалить ветку надо выполнить команду:

    git branch -d <Название ветки>
    
## Удаленные репозитории
    
Удаленный репозиторий это облачное хранилище ваших файлов. Позволяет работать с проектоми из любой точки мира, где есть Интернет.
