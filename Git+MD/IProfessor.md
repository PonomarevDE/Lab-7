## Описание интерфейса IProfessor

Интерфейс предназначен для работы с методами класса [Professor](Professor.md)

### Реализация интерфейса

- +ADD(PROFESSOR:[Professor](Professor.md) :INT - Функция добавляющая профессора
- +DEL(ID:INT)  : INT - Функция удаляющая профессора
- +SAVE (PROFESSOR:[Professor](Professor.md)) :INT - функция сохраняющая изменения профессора 
- +FIND(SORT:STRING,ASKORDESK:STRING,ID:INT,FIO:STRING,PHONE:STRING,SEX:BOOL,COURSE:[COURSE](Course.md),PAGE:INT,COUNT:INT):LIST<[Professor](Professor.md)> - Функция осуществляющая поиск, сортировку, фильтрацию списка профессоров
- +GET_COURSES_LIST(ID:INT,STATUS:BOOL,PROFESSOR:[Professor](Professor.md)):LIST<[COURSE](Course.md)> - функция Позволяющая получить список курса профессора
- +GET_ALL_CLASS(ID:INT,TIME_START:DATETIME,TIME_END:DATETIME):LIST<[CLASS](Class.md)> - функция позволяющая получить все занятия профессора
