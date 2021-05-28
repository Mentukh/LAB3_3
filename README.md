# Лабораторна робота 3
## Тема: _Методи обходу та модифікації графів_
## Мета роботи: _Навчитись застосовувати алгоритми обходу графів, побудови дерева шляхів та мінімального зв’язного дерева_
## Хід роботи

1. За допомогою лабораторного макету побудувати випадковий неорієнтований граф `G={8,12}`:
    
    ![alt text](https://github.com/Mentukh/LAB3_3/blob/main/1.jpg "Граф")
    
    1. Побудувати дерево за алгоритмом обходу в ширину (BFS); (для 2-х різних вершин)
          
           Порядок обхода: 0 1 2 3 4 5 6 7
           
          ![alt text](https://github.com/Mentukh/LAB3_3/blob/main/2.jpg "Дерево1")
          
           
           Порядок обхода: 4 1 2 3 5 6 7 0
           
          ![alt text](https://github.com/Mentukh/LAB3_3/blob/main/3.jpg "Дерево2")
           
    3. Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?
    
           Ні, не будуть однаковими
          
    5. Побудувати дерево за алгоритмом обходу в глибину (DFS); (для 2-х різних вершин)
           Порядок обхода: 1 0 2 4 3 5 6 7
           
          ![alt text](https://github.com/Mentukh/LAB3_3/blob/main/4.jpg "DFS")
          
            Порядок обхода: 5 2 0 1 3 4 6 7
            
          ![alt text](https://github.com/Mentukh/LAB3_3/blob/main/5.jpg "DFS2")
           
    7. Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?
    
             Ні, не будуть однаковими
1. За допомогою лабораторного макету побудувати випадковий орієнтований граф `G={6,10}`:
     ![alt text](https://github.com/Mentukh/LAB3_3/blob/main/6.jpg "Граф2")
 
    1. Побудувати дерево за алгоритмом обходу в ширину (BFS);
           
           
          ![alt text](https://github.com/Mentukh/LAB3_3/blob/main/7.jpg "BFS")
          
    3. Яка вершина (вершини) буде знайдена останньою?
            4 
            
    5. Визначити чи існують цикли. Вказати послідовність ребер і їх довжину.
           Так граф має цикл, 0=>5=>2=>1=>0 довжина 4
           
     
    7. Визначити кількість хвиль, які пройдуть по ребрах доки буде виявлена остання вершина.
    
            Для цього потрібно 3 хвилі
              
    


## Висновок

    В цій лабораторінй роботі були вивчені алгоритми обходу графів, побудови дерева шляхів та мінімального зв’язного дерева. В процесі виконання були побудованні різні графи, та застосовані до них вивчені алгоритми.
