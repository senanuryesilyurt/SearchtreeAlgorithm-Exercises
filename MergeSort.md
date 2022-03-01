## Merge Sort Project

    Array : [16,21,11,8,12,22]
1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
---
### Solution
1. [16,21,18] - [8,12,22]   
2. [16] [21,18] - [8] [12,22]
3. [16] [18,21] - [8] [12,22]
4. [8,16] - [12,18,21,22]
5. [8,12,16,18,21,22]

Big-O Notasyonu : O(nlogn)
