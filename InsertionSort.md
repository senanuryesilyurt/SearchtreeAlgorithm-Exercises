## Insertion Sort Project

    Array 1 : [22,27,16,2,18,6]
##### a) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
##### b) Big-O gösterimini yazınız.
##### c) Time Complexity; Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
##### d) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 
---
 
    Array 2 : [7,3,5,8,2,9,4,15,6] 
##### a) Yukarıdaki dizinin Insertion Sort'a göre ilk 4 adımını yazınız.
---

### Solution
##### a ;
1.  **[22]**,27,16,2,18,6
2.  **[22,27]**,16,2,18,6
3.  **[16,22,27]**,2,18,6
4.  **[2,16,22,27]**,18,6
5.  **[2,16,18,22,27]**,6
6.  **[2,6,16,18,22,27]**
##### b ;
Elimizde n elemanlı bir dizi olduğunu varsayarsak ; 

    n + (n-1) + (n-2) ... 
    n*(n+1) / 2 = (n^2 + n) / 2
Big-O notasyonu : O(n^2)
##### c ;
Worst case: O(n^2)  
Best case: O(1)  
Average case: O(n/2)
##### d;
18 Sayısı dizi içinde aranmak istenildiğinde "dizinin ortasında sayılabilir" durumundan dolayı **average case** durumuna girer.

##### a ;
1. **[7]**,3,5,8,2,9,4,15,6
2. **[3,7]**,5,8,2,9,4,15,6
3. **[3,5,7]**,8,2,9,4,15,6
4. **[3,5,7,8]**,2,9,4,15,6



