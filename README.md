# Test_project Lets try out gitHub

# Работа с удаленными репозиториями
Для работы с удаленным репозиторием необходимо скачать его на свой ПК путем введения команды:
git clone {адрес удаленного репозитория}

Для выгрузки локального репозитория на общий сервис необходимо произвести несколько команд:
+ git remote add origin {адрес удаленного репозитория} // Эта команда связывает локальный репозиторий с удаленным
+ git branch -M main // Эта команда указывает какая ветка будет основной
+ git push -u origin main // Эта команда направляет то, что есть в локальнм репозитории в удаленный

Чтобы взять актуальные изменения с удаленного репозитория в свой локальный репозитрий и сделать слияние всех изменений с моими необходимо ввести команду:
git pull

Изменили файл

Согласен!)