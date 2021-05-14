## Описание интерфейса IContract

Интерфейс предназначен для работы с методами класса [Contract](Contract.md)

### Реализация интерфейса
- +ADD(CONTRACT:[Contract](Contract.md)) :INT - Функция добавляет новый Договор
- +DEL(ID:INT)  : INT - Функция удаляет договор
- +SAVE (CONTRACT:[Contract](Contract.md)) :INT - Функция сохраняет изменения в договоре
- +PAY(ID:INT,PAYMENT:MONEY):MONEY - Функция позволяет провести оплату
- +GET_PAYMENT_LIST(ID:INT,TIME:DATETIME,SUM:MONEY,CONTRACT:[Contract](Contract.md)):LIST<PAYMENT> - Функция позволяет получить список оплат
- +FIND(SORT:STRING,ASKORDESK:STRING,STUDENT:[STUDENT](Student.md),COURSE:[COURSE](Course.md),ID:INT,COST:MONEY,DEBT:MONEY, DATE:DATETIME,PAYMENT:[PAYMENT](Payment.md),PAGE:INT,COUNT:INT)LIST<[Contract](Contract.md)> - функция Фильтрует Ищет Сортирует
