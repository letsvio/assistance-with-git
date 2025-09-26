# 📝 Шпаргалка Git & GitHub

## 🔹 Настройка

``` bash
git config --global user.name "Твоё Имя"  # Установить имя 
git config --global user.email "email@example.com" # Установить emai
git config --list   # Проверить настройки
```

## 🔹 Создание и инициализация

``` bash
git init                 # Инициализация репозитория в текущей папке
git clone <url>          # Клонирование репозитория
```

## 🔹 Основные операции

``` bash
git status               # Проверить состояние репозитория
git add <файл>           # Добавить файл в индекс (staging)
git add --all                # Добавить все изменения
git commit -m "сообщение" # Зафиксировать изменения
git log                  # История коммитов
git diff                 # Посмотреть изменения
```

## 🔹 Работа с ветками

``` bash
git branch               # Список веток
git branch <имя>         # Создать новую ветку
git checkout <ветка>     # Переключиться на ветку
git checkout -b <ветка>  # Создать и перейти
git merge <ветка>        # Слить ветку в текущую
git branch -d <ветка>    # Удалить ветку (локально)
```

## 🔹 Работа с удалённым репо (GitHub)

``` bash
git remote add origin <url>  # Привязать удалённый репозиторий
git remote -v                # Проверить привязку

git push -u origin main      # Первый пуш ветки main
git push                     # Отправить изменения
git pull                     # Получить изменения
git fetch                    # Скачать изменения без слияния
```

## 🔹 Отмена изменений

``` bash
git restore <файл>           # Вернуть файл из последнего коммита
git reset HEAD <файл>        # Убрать файл из staging
git reset --hard HEAD        # Откатить все изменения
```

## 🔹 Работа с тегами

``` bash
git tag v1.0                   # Создать тег
git tag                        # Список тегов
git push origin v1.0           # Отправить тег
```

## 🔹 Полезное

``` bash
git stash                      # Сохранить незакоммиченные изменения
git stash pop                  # Вернуть изменения из stash
git reflog                     # История всех действий
```


