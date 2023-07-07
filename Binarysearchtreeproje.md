[7,5,1,8,3,6,0,9,4,2]

# SORU 1
Yukarıdaki dizinin Binary-Search-Tree aşamalarını yazınız.

# CEVAP 1

Root olarak "5" seçelim.

-İlk elemanımız 7, 5'ten büyük olduğu için ağacın sağ dalına yazalım.
-Üçüncü elemanımız 1, 5'ten küçük olduğu için sol dalına yazalım.
-Dördüncü elemanımız 8, 5'ten ve 7'den büyük olduğu için sağ dala yazılır.
-Beşinci elemanımız 3; 5'ten küçük olduğu için sol dalına, 1'den büyük olduğu için 1'in sağ dalına yazılır. 
-Altıncı elemanımız 6; 5'ten büyük olduğu için ağacın sağ dalına, 8'den küçük olduğu için sol dalına yazılır.
-Yedinci elemanımız 0, hem 5 hem de 1'den küçük olduğu için ikisinin de sol kolu takip edilerek yazılır.
-Sekizinci elemanımız 9, hem 5 hem de 8'den büyük olduğu için ikisinin de sağ kolu takip edilerek yazılır.
-Dokuzuncu elemanımız 4; 5'ten küçük 1 ve 3'ten büyük olduğu için 3'ün sağ alt koluna yazılır.
-Onuncu elemanımız 2; hem 5 hem de 4'den küçük oldupu için 4'ün sol dalına yazılır. 


                 5
            /       \
           1         7
          / \         \
         0   3         8
              \       / \ 
               4     6   9 
              /
             2  