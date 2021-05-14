## Описание интерфейса IStudent

Интерфейс предназначен для работы с методами класса [Student](Student.md)

### Реализация интерфейса

- +ADD(STUDENT:[STUDENT](Student.md)) :INT - Функция добавляет нового студента
- +DEL(ID:INT)  : INT - функция удаляет студента
- +SAVE (STUDENT:[STUDENT](Student.md)) :INT - функция сохраняет изменения в студенте
- +GET_DEBT(ID:INT,):MONEY - Функция позволяет Получить имеющийся долг
- +GET_CONTRACTS_LIST(ID:INT,):LIST<[CONTRACT](Contract.md)> - Функция позволяет получить список всех Договоров
- +GET_COURSES_LIST(ID:INT,STATUS:BOOL):LIST<[COURSE](Course.md)> - Функция позволяет получить список всех Курсов
- +GET_ALL_TODAY_CLASS(ID:INT,TIME_START:DATETIME,TIME_END:DATETIME):LIST<[CLASS](Class.md)> - Функция позволяет посмотреть рассписание
- +FIND(SORT:STRING,ASKORDESK:STRING,ID:INT,FIO:STRING,PHONE:STRING,SEX:BOOL,CONTRACT:[CONTRACT](Contract.md), COURSE:[COURSE](Course.md),PAGE:INT,COUNT:INT):LIST<[STUDENT](Student.md)> - Функция поиска сортировки фильтрации. 
