# Подсказки по GIT

Задать имя пользователя:
```sh
git config --global user.name "Name”
```

задать адрес электронной почты:
```sh
git config --global user.email "Routray@1.com”
```

Проверка статуса репозитория:
```sh
git status
```

Команда инициализации репозитория:
```sh
git init
```

Выбор файла для работы:
```sh
git add <filename>
```

Внесение изменений однострочным сообщением:
```sh
git commit -m "Message”
```

Журнал изменений:
```sh
git log
```

Краткий журнал изменений:
```sh
git log --oneline
```

Просмотр истории коммитов с визуализацией всех веток:
```sh
git log --graph
```

Возврат к версии изменений по хэшу:
```sh
git checkout <hash>
```

Возврат к последней версии изменений:
```sh
git checkout master
```

Переключиться между ветками:
```sh
git checkout branch_name
```

Для создания ветки и автоматического перехода на ветку:
```sh
git checkout -b new_branch_name
```

Просмотр изменений до коммита:
```sh
git diff
```

Просмотр списка веток:
```sh
git branch
```

Создание новой ветки:
```sh
git branch branch_name 
```

Удаление ветки:
```sh
git branch -d existing_branch_name
```

Принудительное удаление ветки:
```sh
git branch -D existing_branch_name
```

Сохранить изменения с ветки branch_name в текущую выбранную ветку:
```sh
git merge branch_name
```

Клонировать репозиторий из GitHub на свой ПК:
```sh
git clone
```

Добавить удалённый репозиторий и присвоить ему имя (shortname):
```sh
git remote add <shortname> <url>
```

Отправка изменений с ПК в удалённый репозиторий (с ПК в GitHub):
```sh
git push -u origin main
```

Получение изменений из удалённого репозитория (из GitHub на свой ПК):
```sh
git pull
```