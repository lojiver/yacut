# Сервис для создания коротких ссылок

[![Praktikum](https://yastatic.net/q/logoaas/v2/%D0%AF%D0%BD%D0%B4%D0%B5%D0%BA%D1%81.svg?circle=black&color=000&first=white)](https://practicum.yandex.ru/profile/backend-developer/) [![Praktikum](https://yastatic.net/q/logoaas/v2/%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%BA%D1%83%D0%BC.svg?color=000)](https://practicum.yandex.ru/profile/backend-developer/)
обучающий проект **by Anna Gorbunova**

## Описание проекта
Сайт для создания коротких ссылок. Можно вводить свой вариант короткой ссылки или получать автосгенерированный.

## Использованные технологии
- flask==2.0.2
- sqlalchemy==1.4.29

## Инструкции по запуску
Клонировать репозиторий и перейти в него в командной строке:

```
git clone 
```

```
cd yacut/
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

* Если у вас Linux/macOS

    ```
    source venv/bin/activate
    ```

* Если у вас windows

    ```
    source venv/Scripts/activate
    ```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Запустить сервер на локальной машине:
```
flask run
```
В браузере открыть страницу http://127.0.0.1:5000/

## Требования к версии Python
Работает на Python 3.7.0
