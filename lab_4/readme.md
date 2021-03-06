# Лабораторна робона №4
## Тема: _Алгоритми пошуку найкоротших шляхів_
## Мета роботи: _Навчитись застосовувати алгоритми пошуку найкоротших шляхів та застосовувати їх в телекомунікаційних мережах._

## Результати виконання роботи:


1. За допомогою лабораторного макету побудувати випадковий неорієнтований зважений граф з `V=6` та `E=10` 

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_4/screen/1.png)


Побудувати дерево шляхів з вершини `N` за алгоритмом Дейкстри

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_4/screen/2.png)

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_4/screen/2_1.png)

2. Для того ж графа побудувати дерево шляхів з вершини `N` за алгоритмом Беллмана-Форда;

![image](https://github.com/SergioPylyp/Pylyp_LAB_TOTK_2021/blob/main/lab_4/screen/3.png)


3. Вказати який з алгоритмів виконується швидше:
    1. порівняти за кількістю кроків для знаходження найкоротшого шляху;
       
            В алгоритмі Дейкстри кількість кроків значно менша адже він шукає відразу найкоротший шлях і в моєму завданні алгоритм Дейкстри виконав 4 кроки а Беллмана-Форда 7.       

    2. порівняти за кількістю відвіданих вершин на кожному кроці;
    
            Дейкстри відвідував меншу клькість вершин ніж Беллмана-Форда

4. Чи знайдені маршрути за алгоритмом Дейкстри та Беллмана-Форда однакові?
    1. Якщо ні, вказати які та чому;
    
            Так, вони є однакові
       
    2. Чи існують маршрути з однаковою метрикою? Які?
                
            Ні, не існують 
    
5. Вважаючи, що коефіцієнти ребер вказують на пропускну здатність в Мбіт/с, знайти пропускну здатність кожного шляху визначеного за алгоритмом Дейкстри та Беллмана-Форда.
    1. Які шляхи мають максимальну пропускну здатність, чому?

            0-(5)-1=5
            0-(5)-1-(4)-2=4
            0-(5)-1-(4)-2-(1)-3=1
            0-(3)-5-(6)-4=3
            0-(3)-5=3
            Максимальна пропускна здатність на шляху 0-1 яка складає 5 мб/с
       
    2. Чи є шляхи які на якомусь відрізку мережі використовують менше половини пропускної здатності ребра?
            
            Є, при переході 0-3
       
    3. Чи можливе одночасне існування потоків із вершини `N` до всіх інших із розрахованою пропускною здатністю кожного шляху? Чому?
    
            Ні, не можливе. При використанні максимальної пропускної здатності не вистачає її на інші вершини тому вони є не активними(робочими)
    
## Висновок:

    На даній лабораторній роботи ми навчились застосовувати алгоритми пошуку найкоротших шляхів та застосовувати їх в телекомунікаційних мережах.
