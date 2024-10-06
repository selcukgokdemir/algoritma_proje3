## soru  
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

##  cevap 
```  

root  7

*     7           5 , 7'den küçük olduğu için soluna eklenir.
     /
    5


*     7           1, 7 'den küçük olduğu için soluna gider soldaki 5'den küçük olduğu için 5 inde soluna eklenir.
     /
    5
   /
  1

*     7           8, 7'den büyük olduğu için sağa eklenir.
     / \
    5   8
   /
  1

*     7           3, 7'den küçük sola alttaki 5'de de küçük soluna gider ama alttaki 1'den büyük olduğu için 1'in sağına eklenir
     / \
    5   8
   / 
  1
    \
     3

*     7            6, 7'den ve küçük sola ama alttaki 5 den büyük olduğu için 5 in sağına yazılır
     / \
    5   8
   / \ 
  1   6
    \
     3


*     7            0, 7'den ve küçük sola 5'den de küçük sola ve sol alttaki 1'den de küçük sola eklenir
     / \
    5   8
   / \ 
  1   6
 / \
0   3

*     7            9, 7'den ve büyük hemen altındaki 8'den de büyük olduğu için 8'in sağına eklenir
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3

*     7         4, 7'den ve küçük sola 5'den de küçük sola 1'den büyük sağa 3'den de büyük sağa eklenir
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4

*     7         2, 7'den ve küçük sola 5'den de küçük sola 1'den büyük sağa 3'den de küçük sola eklenir
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4

``` 

