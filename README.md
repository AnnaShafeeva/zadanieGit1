# **Менеджер продаж**
### При помощи этого приложения можно:
1. Вносить данные по количеству проданных единиц товаров;
2. Отслеживать максималное количество проданных товаров за необходимый период:
    * час;
    * смену;
    * день;
    * неделю и т.д.

### Для работы приложения нужно:
1. Создать новую переменную типа `SalesManager`:
```java
 SalesManager day1 = new SalesManager(new int[]{35, 38, 36, 40, 39, 45, 43});
```
Где вместо имени переменной `day1` можно указать нужный период, например `week`, `month` и т.д.
2. В скобках `{ }` фиксировать проданное количество товаров через `,`;
3. В стрoке:
```java
System.out.println("Максимальное количество проданных позиций в течение дня" + day1.max() + " шт");
```
в случае присвоения другого имени переменной типа `SalesManager` (п.1), необходимо вставить его же в выражение`day1.max()`
всесто `day1`.
4. Полученное максимальное значение выведется в консоль после запуска программы.
5. При необходимости сохранять полученные значения, копируйте строки:
```java
SalesManager day1 = new SalesManager(new int[]{35, 38, 36, 40, 39, 45, 43});
        
System.out.println("Максимальное количество проданных позиций в течение дня" + day1.max() + " шт");
```
не забывая присваивать новое имя и значения.

### Приятной работы с приложением!
![котик](https://bipbap.ru/wp-content/uploads/2017/07/936.jpg)