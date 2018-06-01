# Домашняя работа №9
Для выполнения данного домашнего задания я использовала программу *Notepad++*.

### 1. Удалить все пустые строки.
Для того, чтобы удалить все пустые строки из исходного документа, я использовала регулярное выражение \n\r и заменила на \0.
![](https://github.com/nastyaprokhorova/hw9/blob/master/1.png)

Однако с помощью этого выражения удалось удалить не все пустые строки. Поэтому я использовала регулярное выражение [\s]*$, которое я заменила на \0, чтобы убрать пробелы в начале строк.
![](https://github.com/nastyaprokhorova/hw9/blob/master/2.png)

### 2. Найти всех князей и города, имя и название которых оканчивается на "слав".
Чтобы выполнить данное задание, я использовала регулярное выражение [А-Я]+\w+слав+\w*. В результате получилось 592 вхождения.
![](https://github.com/nastyaprokhorova/hw9/blob/master/3.png)

### 3. Найти все упоминания Новгорода.
Для выполнения данного задания, я использовала регулярное выражение (Новѣ?город[а-я]?|Новъ?город[а-я]?|Новгородц[а-я]?|Новагород[а-я]?|Новугород[а-я]?|Новгород[а-я]?). В результате получилось 59 вхождений.
![](https://github.com/nastyaprokhorova/hw9/blob/master/4.png)

## Бонусное задание
Я выполнила бонусное задание в несколько действий. Я вставляла пробелы после необходимых знаков препинаний.
![](https://github.com/nastyaprokhorova/hw9/blob/master/бонус1.png)
![](https://github.com/nastyaprokhorova/hw9/blob/master/бонус2.png)
![](https://github.com/nastyaprokhorova/hw9/blob/master/бонус3.png)
![](https://github.com/nastyaprokhorova/hw9/blob/master/бонус%204.png)
![](https://github.com/nastyaprokhorova/hw9/blob/master/бонус5.png)
![](https://github.com/nastyaprokhorova/hw9/blob/master/бонус6.png)
[Итоговый файл](https://github.com/nastyaprokhorova/hw9/blob/master/result.txt) я прикрепила в репозиторий.
