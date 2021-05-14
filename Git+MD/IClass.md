## Описание интерфейса IClass

Интерфейс предназначен для работы с методами класса [Class](Class.md)

### Реализация интерфейса

- +ADD(CLASS:[Class](Class.md)) :INT - Добавить новое занятие
- +DEL(ID:INT)  : INT - Удалить занятие
- +SAVE (CLASS:[Class](Class.md)) :INT - Сохранить изменение в занятии 
- +FIND(SORT:STRING,ASKORDESK:STRING,PROFESSOR:[PROFESSOR](Professor.md),TIME:DATETIME,OFFICE:[OFFICE](Office.md),ID:INT,COURSE:[COURSE](Course.md),PAGE:INT,COUNT:INT):LIST<[Class](Class.md)> - Функция фильтрует сортирует ищет
