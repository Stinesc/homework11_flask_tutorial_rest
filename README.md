# homework11_flask_tutorial_rest
Управление зависимостями производится с помощью pipenv.
Установка pipenv производится командой:
```
pip install pipenv
```
Установка зависимостей, включая dev зависимости, производится командой:
```
pipenv install --dev
```
Далее необходимо выполнить команды:
```
export FLASK_APP=flaskr
export FLASK_ENV=development
```
Необходимо инициализировать БД командой:
```
flask init-db
```
Запуск веб-приложения производится командой:
```
flask run
```
