Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/comaash/kittygram_backend.git

cd kittygram_backend
```
Cоздать виртуальное окружение:

```
python3 -m venv env
```

Активировать виртуальное окружение:

Если у вас Linux/macOS:
```
source env/bin/activate
```
Если у вас windows:
```
source env/scripts/activate
```

Установить пакетный менеджер
```
python3 -m pip install --upgrade pip
```
Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```
Заполнить файл .env по образцу .env.example

Выполнить миграции:
```
python3 manage.py migrate
```
Запустить проект:
```
python3 manage.py runserver
```
