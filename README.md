#Karma hackaton Offline

##Создание приложение локального мультивалютного холодного кошелька

Цель: реализовать безопасный способ создания пары публичного/приватного ключей

Итерации актора:

- Выбрать в выпадающем меню алгоритм хеширования
- Выбрать монету, к которой создавать кошелёк
- Нажать на генерацию пары ключей
- На экране появятся адрес и приватный ключ, который пользователь может сохранить удобным ему образом
- К адресу и приватному ключу создаются их qr-code аналоги, автоматически сохраняющиеся в корневой папке
- Пользователлю предлагается распечатать qr-code на шаблоне

Для успешной работы необходимо установить следующие компоненты:
    ```printf(pip3 install pyqt5, sha3, ecdsa, bitcoin --user)```
