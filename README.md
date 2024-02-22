# 2FA
## Описание:
  Данный репозиторий представляет собой реализацию регестрации на сайте с использованием технологии двухфаторной аутентификации, написанную на языке `Python` с использованием фреймворка `Flask`, и библиотек `qrcode`, `pyotp`. К репозиторию не приложены файлы `venv`, так что после установки, для корректной работы программы, требуется скачать все необходимые библиотеки (_см. **Использование**_).
## Использование:
1. Скачать файлы репозитория
2. Иметь итерпретатор `Python` (_я использовал версию_ `3.12.2` [ссылка под Windows x64](https://www.python.org/ftp/python/3.12.2/python-3.12.2-amd64.exe))
3. Установить библиотеки (с помощью встроенного `pip`):
   - `Flask` (v. 3.0.2)
   - `Flask-SQLAlchemy` (v. 3.1.1)
   - `pyotp` (v. 2.9.0)
   - `qrcode` (v. 7.4.2)
4. Запустить `main.py` и перейти по выданному _URL_ (localhost)
