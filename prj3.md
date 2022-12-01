## Binary Search Tree

---

1.Soru: [7,5,1,8,3,6,0,9,4,2] Dizinin Binary-Search-Tree aşamalarını yazınız.

**Binary-Search-Tree de ağacın sol tarafına küçük, sağ tarafına ise büyük elemanlar yazılarak ilerlenir.**

**_Root => 7 olara kabul edelim._**

> CEVAP:

> > 1 --> 7 > 5 => 5 , 7'nin soluna

> > 2 --> 7 > 1 , 5 > 1 => 1 , 5'in soluna

> > 3 --> 7 < 8 => 8 , 7'nin sağına

> > 4 --> 7 > 3 , 5 > 3 , 1 < 3 => 3 , 1'in sağına

> > 5 --> 7 > 6 , 5 < 6 => 6 , 5'in sağına

> > 6 --> 7 > 0 , 5 > 0 , 1 > 0 => 0 , 1'in soluna

> > 7 --> 7 < 9 , 8 < 9 => 9 , 8'in sağına

> > 8 --> 7 > 4 , 5 > 4 , 1 < 4 , 3 < 4 => 4 , 3'ün sağına

> > 9 --> 7 > 2 , 5 > 2 , 1 < 2 , 3 < 2 => 2 , 3'ün soluna yazılır.

> SONUÇ =>
```
                  7          -> Root Satırı
                 / \
                /   \
               5     8       -> 1. Düğüm Satırı
              / \     \
             /   \     \
            1     6     9    -> 2. Düğüm Satırı
           / \
          /   \
         0     3             -> 3. Düğüm Satırı
              / \
             /   \
            2     4          -> 4. Düğüm Satırı
```

---
 ## Hakan Çoban

 <a href="www.patika.dev">Patika.dev</a>