#SELECTION SORT PROJESI
- [22, 27, 16, 2, 18, 6] -> Insertion Sort [-n}
- [2, 27, 16, 22, 18, 6] -> 2 sayısı en küçük olarak bulunur ve en baştaki 22 sayısı ile yer değiştirir.  [n-1]
- [2, 6, 16, 22, 18, 27] -> 2 sayısı hariç en küçük rakam olan 6 bulunur ve ikinci sıradaki 27 sayısı ile yer değiştirir.[n-2]
- [2, 6, 16, 18, 22, 27] -> 2 ve 6 sayısı hariç en küçük sayı 16 dokunulmaz ve sonraki en küçük sayı 18 bulunur ve 22 sayısı ile yer değiştirir.Sıralama işlemi biter.[n-3]
- [2, 6, 16, 18, 22, 27] -> [1]


n tane değer için yapılacak işlem n+(n-1)+(n-2)+(n-3)+.........+1 dir. Bu işlemlerin toplamı sonucundan (n^2+n)/2 denklemini buluruz. Bu denklemi donime eden değer n^2 olduğu için O(n^2)



-18 sayısı dizinin ortasında olduğu için Avarage Case olur.

 [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort' a göre ilk dört adımı:
- 1- [7, 3, 5, 8, 2, 9, 4, 15, 6]
- 2- [2, 3, 5, 8, 7, 9, 4, 15, 6]
- 3- [2, 3, 4, 8, 7, 9, 5, 15, 6]
- 4- [2, 3, 4, 5, 7, 9, 8, 15, 6]
- 5- [2, 3, 4, 5, 6, 9, 8, 15, 7]

 ----------------------------------------------------------------------------------------------------------------------------------------------------------------------

- [16,21,11,8,12,22] -> Merge Sort
- [16,21,11]    [8,12,22]
- [16,21] [11]  [8,12] [22]
- [16] [21] [11] [8] [12] [22]
- [16,21] [11,8] [12,22]
- [8,11,16,21] [12,22]
- [8,11,12,16,21,22]

- Big-O notation --> O(n*logn)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------


-[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları
-[0,1,2,3,4, 5 ,6,7,8,9] İlk önce Root bulunur: 5 dir.
        5 
     /    \
   3       7
  / \     / \
 2  4    6    8
/ \             \
0  1              9 
             

 
