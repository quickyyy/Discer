
![Logo](https://cdn.discordapp.com/attachments/762363252143161355/1140292912098332672/361b6cfc52462fbc3928adeb828df2d9.png)

[![telegram](https://img.shields.io/badge/Мой%20Телеграм%20Блог-0099cc)](https://t.me/bredcookie)



## Description
    DISCER - Образован от Discord и Checker. Второй проект из цикла чекеров от меня, имеет
    проверку на авторег, нитро, почту, телефон, друзей и никнейм.

Умеет парсить из tokens.txt, проходится по всем директориям в папках пока не умеет, скоро добавлю
## Пример лога в файле
```
📝Username - nickname
 🪨 Does not have an active nitro sub
 ❌ It seems like the account is auto-reg
 📋 token - *its a token, ok?*
 📫email - google@gmail.com
 📱phone - None
 🫂friends - []
```
## Пример лога в консоли
```
✅ Valid - *its a token, ok?*
📋 Getting info about token..
📝Username - nickname
 ❌ Is seems like account auto-reg
 🪨 Dont have active nitro sub
 📫email - google@gmail.com
 📱phone - None
 🫂friends - []
```
## Установка и использование


```python
  pip install -r requirements.txt
  py main.py
```
    Далее все интуитивно понятно, программа спрашивает и распрашивает вас обо всем.
## TODO

- Конфиг с настройками
- Графические изменения
- *Добавление прокси к чеку*
- Отстук в телеграм
- Проверка на администрирование в каналах
- *Проспам по токенам*
- ~~*Многопоток*~~ Реализовано
## 🔗 Links
[![telegram](https://img.shields.io/badge/Мой%20Телеграм%20Блог-0099cc)](https://t.me/bredcookie)
Да, второй раз, а вы что хотели?
## License

[MIT](https://choosealicense.com/licenses/mit/)

