## Описание интерфейса IPayment

Интерфейс предназначен для работы с методами класса [Payment](Payment.md)

### Реализация интерфейса

- +ADD(PAYMENT:[Payment](Payment.md)) :INT - Функция позволяет добавить оплату
- +DEL(ID:INT)  : INT - функция позволяет удалить оплату
- +SAVE (PAYMENT:[Payment](Payment.md)) :INT - Функция позволяет сохранить изменения в оплате
- +FIND(SORT:STRING,ASKORDESK:STRING,ID:INT,SUM:MONEY,TIME:DATETIME,CONTRACT:[Contract](Contract.md),PAGE:INT,COUNT:INT)LIST<[Payment](Payment.md)> - функция фильтрует ищет сортирует 
