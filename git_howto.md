# Подсказки по GIT

Задать имя пользователя
```sh
git config --global user.name "Name”
```

задать адрес электронной почты
```sh
git config --global user.email "Routray@1.com”
```

Проверка статуса репозитория
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

Внесение изменений однострочным сообщением
```sh
git commit -m "Message”
```

Журнал изменений
```sh
git log
```

Краткий журнал изменений. 
```sh
git log --oneline
```

Возврат к версии изменений по хэшу:
```sh
git checkout <hash>
```

Возврат к последней версии изменений:
```sh
git checkout master
```

Просмотр изменений до коммита:
```sh
git diff
```

