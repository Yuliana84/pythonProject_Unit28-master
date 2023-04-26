#Unit28
Задание 28.9.11 - ИСПОЛЬЗОВАНИЕ БИБЛИОТЕКИ PYDANTIC В АВТОТЕСТАХ

По заданию написаны реализация API-методов для http://restful-booker.herokuapp.com/apidoc/index.html и тесты с использованием библиотеки pydantic для проверки формата и обязательности данных запроса и ответа.

/api/booking.py - библиотека API-методов
/resources/prepary_data.py - данные для тестов
/resources/booking_model.py - объекты pydantic - модели для поверки данных запроса и ответа
/tests/test_booking.py - тесты

Не проходят тесты на API-методы PUT и DELETE, т.к. эти методы, видимо, запрещены, получаем статус 403 - Forbidden. 
