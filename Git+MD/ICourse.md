## Описание интерфейса ICourse

Интерфейс предназначен для работы с методами класса [Course](Course.md)

### Реализация интерфейса

- +ADD(COURSE:[Course](Course.md)) :INT - функция позволяет добавить новый курс
- +DEL(ID:INT)  : INT - функция позволяет удалить курс
- +SAVE (COURSE:[Course](Course.md)) :INT - функция позволяет сохранить изменения
- +GET_STUDETS(ID:INT,):LIST<[STUDENT](Student.md)> - функция позволяет получить студентов курса
- +GET_ALL_CLASS(ID:INT,TIME_START:DATETIME,TIME_END:DATETIME):LIST<[CLASS](Class.md)> - функция позволяет получить все занятия курса
- +FIND(SORT:STRING,ASKORDESK:STRING NAME:STRING,COST:MONEY,DURATION:INT,PROFESSOR:[PROFESSOR](Professor.md),ID:INT,PAGE:INT,COUNT:INT)LIST<[Course](Course.md)> - фунция фильтрует ищет сортирует 
