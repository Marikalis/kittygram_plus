## How to start the project:
Clone the repository and go to it via the command line:

```
git clone https://github.com/yandex-praktikum/kittygram_plus.git
cd kittygram_plus
```

Create and activate a virtual environment:

```
python3 -m venv env
source env/bin/activate
```

Install dependencies from the requirements.txt file:

```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

Perform migrations:

```
python3 manage.py migrate
```

Start the project:

```
python3 manage.py runserver
```

========================================

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram_plus.git
```

```
cd kittygram_plus
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
