# INSERTION SORT(PROJE-1) MERGE SORT(PROJE-2) BİNARY SEARCH TREE PROJESİ(PROJE-3) 

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
 1-SORT TÜRÜNE GÖRE AŞAMALAR
   A) 2 27 16 22 18 6
   B) 2 6 16 22 18 27
   C) 2 6 16 18 22 27
 
2. Big-O gösterimini yazınız ?
  A ALGORİTMASI: O(6)
  B ALGORİTMASI: O(log6)= 2x=6
  
4. Time Complexity:
    Average case: Aradığımız sayının ortada olması; 18
    Worst case: Aradığımız sayının sonda olması, 27
    Best case: Aradığımız sayının dizinin en başında olması. 2
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 18 SAYISI AVERAGE CASE KAPSAMINA GİRER.

5.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
   1. 2,3,5,8,7,9,4,15,6
   2. 2,3,4,8,7,9,5,15,6
   3. 2,3,4,5,7,9,8,15,6
   4. 2,3,4,5,6,9,8,15,7
   
PROJE-2
[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
              [16,21,11,8,12,22]
           1: [16,21,11] , [8,12,22]
           2: [16,21], [11] -[8,12] ,[22]
           3: [16] , [21] ,[11] - [8], [12], [22] 
           4. [21,16],[11]-[8,12],[22]
           5. [11,16,21]-[8,12,22]
           6. [8,11,12,16,21,22]
Big-O gösterimini yazınız.
Big-O: O(nlogn)
 
 
 PROJE-3
 [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
                7
              /   \
             5     8
            / \       \
           1   6        9
          /\
         0   3
           /   \
          2      4
         
         ROOT=7
         ROOT X=8
         ROOT Y=5
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.










