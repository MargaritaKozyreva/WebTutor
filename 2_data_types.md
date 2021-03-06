# Часть 2. Типы данных
***

В данном разделе рассматриваются некоторые основные функции преобразования типов данных:

**String()** – Преобразует аргумент в строку.

**Int()** – Преобразует значение аргумента к целому числу.	

**Real()** – Преобразует значение аргумента к вещественному числу.	

**Date()** – Преобразует значение аргумента к типу Дата.	

**XQueryLiteral()** – Преобразует значение аргумента к типу данных, используемому в запросах.	

---

Примеры преобразования типов данных:

    a = 1;
    b = 2;
    c = a + b;
    d = String(a) + "" + String(b);
    e = '13.01.2018';
    f = Date(e) + 2;
    alert("Число - " + c + "\n" + "Строка - " + d + "\n" + "Дата - " + f);

---

Скопируйте приведенный код в тестовый агент на вкладку **"Выполняемый код"** и запустите агент, как это описано в разделе [Как запустить агент?](run_agent.md)

Результат выполнения агента:

![](data_types01.PNG)


***
<dd><li> <a href="README.md"> Возврат к оглавлению</a></dd>
