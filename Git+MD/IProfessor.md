## Описание интерфейса IProfessor

Интерфейс предназначен для работы с методами класса [Professor](Professor.md)

### Реализация интерфейса

- +ADD(PROFESSOR:[Professor](Professor.md) :INT
- +DEL(ID:INT)  : INT
- +SAVE (PROFESSOR:[Professor](Professor.md)) :INT
- +FIND(SORT:STRING,ASKORDESK:STRING,ID:INT,FIO:STRING,PHONE:STRING,SEX:BOOL,COURSE:[COURSE](Course.md),PAGE:INT,COUNT:INT):LIST<[Professor](Professor.md)>
- +GET_COURSES_LIST(ID:INT,STATUS:BOOL,PROFESSOR:[Professor](Professor.md)):LIST<[COURSE](Course.md)>
- +GET_ALL_CLASS(ID:INT,TIME_START:DATETIME,TIME_END:DATETIME):LIST<[CLASS](Class.md)>
