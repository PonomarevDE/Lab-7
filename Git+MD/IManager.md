## Описание интерфейса IManager

Интерфейс предназначен для работы с методами класса [Manager](Manager.md)

### Реализация интерфейса

- +ADD(MANAGER:[MANAGER](Manager.md)) :INT - Функция Добавляет нового менеджера
- +DEL(ID:INT)  : INT - Функция Удаляет Менеджера
- +SAVE (MANAGER:[MANAGER](Manager.md)) :INT - Функция Сохраняет изменения у менеджера 
- +GET_COURSES_LIST(ID:INT,STATUS:BOOL,PROFESSOR:[PROFESSOR](Professor.md)):LIST<[COURSE](Course.md)> - Функция позволяет получить список всех курсов
- +GET_ALL_CLASS(ID:INT,TIME_START:DATETIME,TIME_END:DATETIME):LIST<[CLASS](Class.md)> - Функция позволяет получить список всех занятий 
- +GET_ALL_CONTRACT(ID:INT,DATE:DATETIME):LIST<[CONTRACT](Contract.md)> - Функция позволяет получить список всех контрактов
- +FIND(SORT:STRING,ASKORDESK:STRINGID:INT,FIO:STRING,PHONE:STRING,SEX:BOOL,PAGE:INT,COUNT:INT):LIST<[MANAGER](Manager.md)> - Функция осуществляет поиск, Фильтраци, Сортировку
