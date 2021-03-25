# Звіт до лабораторної роботи №1
### Тема: Дослідження роботи мережі згідно моделі OSI.
### Мета роботи: Дослідити роботу мережевих пристроїв та прослідкувати як опрацьовуються дані на різних рівнях моделі OSI.
### Результати виконання роботи:
3. ping між комп’ютерами що ввімкнені до повторювача (hub) та прослідковуємо передачу пакетів між ними:
-	Пристрою, що отримує
-	Не змінюється, тому що hub лише відправляє пакети на різні входи, а не робить операції над ними
-	1 рівень
-	Є колізіція
-	Кадр знищується
-	2 рівень
-	Знищуються

4.	Запустити команду ping між комп’ютерами що під’єднані до комутатора (switch) та прослідкувати як комутатор опрацьовує дані.
-	Одержувача
-	Ні
-	2 рівень
-	Ні, тому що є mac адреса одержувача.
-	4 компютерів і роутера

5.  Яким пристроям належать МАС адреси що містяться в таблиці?
-	Можливо. Наприклад, до hub`а підключені 2 компютери з різними mac адресами

6.	
-   на 2 рівні
-	Не можливо, тому що switch немає mac адреси
-	Роутер опрацьовує дані. Встановлюється mac адреса роутера.

7.	Запустити команду ping між комп’ютерами що знаходяться в різних мережах та прослідкувати як маршрутизатор опрацьовує пакети.
-	Mac адреса відправника
-	Мережевий шлюз (англ. gateway) — апаратний маршрутизатор або програмне забезпечення для сполучення комп'ютерних мереж, що використовують різні протоколи (наприклад, локальної та глобальної). 
-	Так
-	Не змінюється
-	3 рівень
-	Через порт 0/0 доступна мережа LAN1, через порт 0/1 мережа LAN2

8.
-	Вона змінюється на представлення в шістнадцятко У двохточковій конфігурації адреса HDLC використовується для позначення напрямку передачі - з мережі до пристрою користувача (10000000) або навпаки (11000000).
-	Преамбула слугує для синхронізації.
-	У двохточковій конфігурації адреса HDLC використовується для позначення напрямку передачі - з мережі до пристрою користувача (10000000) або навпаки (11000000).
### Висновок:
На лабораторній роботі досліджували роботу  мережевих пристроїв та прослідкували як опрацьовуються дані на різних рівнях моделі OSI.