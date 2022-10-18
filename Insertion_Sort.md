# Insertion Sort Projesi
Veri Yapıları ve Algoritmalar Patikası, Insertion Sort Projesi

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    - [2,27,16,22,18,6] -> 2 <=> 22
    - [2,6,16,22,18,27] -> 6 <=> 27
    - [2,6,16,22,18,27] -> 16 (no change)
    - [2,6,16,18,22,27] -> 18 <=> 22
    - [2,6,16,18,22,27] -> 22 (no change)
    - [2,6,16,18,22,27] -> 27 (no change) 
    
    "Total Processes => 6"
    
* Big-O gösterimini yazınız.
    - O(n^2)
    
* Time Complexity:
    - Average case: Aradığımız sayının ortada olması
    - Worst case: Aradığımız sayının sonda olması
    - Best case: Aradığımız sayının dizinin en başında olması.
* Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    - Final sort => [2,6,16,18,22,27]
    - Case is Average


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
    - [2,3,5,8,7,9,4,15,6] -> 2 <=> 7
    - [2,3,4,8,7,9,5,15,6] -> 5 <=> 4
    - [2,3,4,5,7,9,8,15,6] -> 8 <=> 5
    - [2,3,4,5,6,9,8,15,7] -> 6 <=> 7
