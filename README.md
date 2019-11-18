# CurrencyRates
Android приложение, которое получает список валют с сервера цб рф по ссылке: https://www.cbr-xml-daily.ru/daily_json.js

В данном приложении реализован следующий функционал - раз в минуту с сервера обновляется курс валют и есть поле для ввода.
В поле вводится количество средств пользователя, при вводе средств происходит расчёт итоговой суммы, 
которую пользователь может получить в любой валюте из списка.

Что можно доработать:
- добавить textColor для курса, который стал выше или ниже с прошлого раза
- добавить явную проверку наличия интернета на устройстве пользователя