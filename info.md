## Основные команды Git

**git init** – инициализация локального репозитория

**git status** – получить информацию от git о его текущем состоянии

**git add “path”**– добавить файл или файлы к следующему коммиту

**git add .** - добавляет все файлы в проекте в отслеживание

**git commit -am “message”** - git add + git commit (Работает 
только после 1-го ручного добавления в отслеживание)

**git commit -m “message”** – создание коммита

**git log**– вывод на экран истории всех коммитов с их хеш-кодами

**git checkout** – переход от одного коммита к другому

**git checkout master** – вернуться к актуальному состоянию и продолжить работу (git checkout main)

**git diff** – увидеть разницу между текущим файлом и закоммиченным файлом
**git branch** – посмотреть список веток в репозитории

**git branch** <название ветки> – создать новую ветку

**git checkout** <название ветки> – переход к другой ветке

**git branch -d** <название ветки> – удалить ветку

**git log --graph** - визуализирует коммиты

**git checkout -b ** <название ветки> -> Создание и переход в новую ветку

**git commit --amend -m “text”** - изменение текста последнего коммита



# Основные команды третьего семинара

> **git clone <url-адрес репозитория>** - – клонирование внешнего репозитория на локальный ПК

> **git pull** - получение изменений и слияние с локальной версией

** git push **– отправляет локальную версию репозитория на внешний