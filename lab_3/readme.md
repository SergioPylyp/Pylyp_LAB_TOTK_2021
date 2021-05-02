# Звіт із лабораторної роботи №3
## Тема: Методи обходу та модифікації графів.
## Мета роботи: Навчитись застосовувати алгоритми обходу графів, побудови дерева шляхів та мінімального зв’язного дерева.
### Виконання роботи
#### I	За допомогою лабораторного макету побудувати випадковий неорієнтований граф G={8,12}:

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/1.png)

1.	Побудувати дерево за алгоритмом обходу в ширину (BFS); (для 2-х різних вершин)


        Для вершини 0 порядок обходу: 0 1 2 6 4 5 7 3

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/2.png)

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/2_1.png)

        Для вершини 7 порядок обходу: 7 2 3 4 0 5 6 1

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/3.png)

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/3_1.png)

2.	Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?


        Не обовязково. У порівнянні 0 та 7  вершин вони будуть різні а в 0 і 5 однакові

3.	Побудувати дерево за алгоритмом обходу в глибину (DFS); (для 2-х різних вершин)


        Для вершини 2 порядок обходу: 2 0 1 6 3 4 5 7

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/4.png)

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/4_1.png)

        Для вершини 6 порядок обходу: 6 1 0 2 4 3 7 5

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/5.png)

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/5_1.png)

4.	Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?


        Не обовязково. Для кожної вершини буде своя топологія хоть і подібна але не однакова

#### II	За допомогою лабораторного макету побудувати випадковий орієнтований граф G={6,10}:

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/6.png)

1.	Побудувати дерево за алгоритмом обходу в ширину (BFS);


        Порядок обходу:  0 5 2 3 1 4

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/7.png)

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/7_1.png)

2.	Яка вершина (вершини) буде знайдена останньою?


        Вершина 4

3.	Визначити чи існують цикли. Вказати послідовність ребер і їх довжину.


        Так, граф має цикл, 0=>5=>2=>1=>0 довжина 4

4.	Визначити кількість хвиль, які пройдуть по ребрах доки буде виявлена остання вершина.


        Для цього потрібно 3 хвилі

5.	Побудувати дерево за алгоритмом обходу в глибину (DFS);


        Порядок обходу: 0 5 2 1 3 4

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/8.png)

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/8_1.png)

#### III	Побудувати дерево шляхів рангом r=4 для випадкового графа G={6,9}.

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/9.png)


![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/10.png)


#### IV	Побудувати мінімальне зв’язне дерево для графа G. Вказати його вагу.

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/11.png)


![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_3/screen/12.png)

        Вага: 5+7+9+3+5=29
        
### Висновок
*В цій лабораторінй роботі були вивчені алгоритми обходу графів, побудови дерева шляхів та мінімального зв’язного дерева. В процесі виконання були побудованні різні графи, та застосовані до них вивчені алгоритми.
