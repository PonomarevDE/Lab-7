## Описание интерфейса IOffice

Интерфейс предназначен для работы с методами класса [Office](Office.md)

### Реализация интерфейса

- +ADD(OFFICE:[Office](Office.md)) :INT - Функция позволяет Добавить новый кабинет
- +DEL(ID:INT)  : INT - Функция позволяет Удалить новый кабинет
- +SAVE (OFFICE:[Office](Office.md)) :INT - Функция позволяет сохранить изменения в кабинете
- +GET_SCHEDULE(ID:INT,TIME_START:DATETIME,TIME_END:DATETIME):LIST<[CLASS](Class.md)> - функция позволяет получить расписание данного кабинета
- +FIND(SORT:STRING,ASKORDESK:STRINGID:INT,CAPACITY:INT,STATE:BOOL,NAME:STRING,PAGE:INT,COUNT:INT);LIST<[Office](Office.md)> - Функция Фильтрует ищет сортирует
