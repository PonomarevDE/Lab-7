## Описание интерфейса IContract

Интерфейс предназначен для работы с методами класса [Contract](Contract.md)

### Реализация интерфейса
- +ADD(CONTRACT:[Contract](Contract.md)) :INT
- +DEL(ID:INT)  : INT
- +SAVE (CONTRACT:[Contract](Contract.md)) :INT
- +PAY(ID:INT,PAYMENT:MONEY):MONEY
- +GET_PAYMENT_LIST(ID:INT,TIME:DATETIME,SUM:MONEY,CONTRACT:[Contract](Contract.md)):LIST<PAYMENT>
- +FIND(SORT:STRING,ASKORDESK:STRING,STUDENT:[STUDENT](Student.md),COURSE:[COURSE](Course.md),ID:INT,COST:MONEY,DEBT:MONEY, DATE:DATETIME,PAYMENT:[PAYMENT](Payment.md),PAGE:INT,COUNT:INT)LIST<[Contract](Contract.md)>
