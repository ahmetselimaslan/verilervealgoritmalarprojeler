## SORU 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

## CEVAP 1

Not: "*" simgesi o ana kadar sıraldığımız verilerin sonuna koyulmuştur.

Birinci Adım :
[22*,27,16,2,18,6]

Birinci Adım : 22 ve 27 aralında zaten sıralı olduğu için işlem yapmıyoruz.
[22,27*,16,2,18,6]

Üçüncü Adım :
[22,16*,27,2,18,6]
[16,22,27*,2,18,6]

Dördüncü Adım :
[16,22,2,27*,18,6]
[16,2,22,27*,18,6]
[2,16,22,27*,18,6]

Beşinci Adım :
[2,16,22,18,27*,6]
[2,16,18,22,27*,6]

Altıncı Adım :
[2,16,18,22,6,27*]
[2,16,18,6,22,27*]
[2,16,6,18,22,27*]
[2,6,16,18,22,27*]

Dizi sıralnmış oldu. : [2,6,16,18,22,27]


## SORU 2

Big-O gösterimini yazınız.

## CEVAP 2

O(n2) 

## SORU 3
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

## CEVAP 3

Average Case.

## SORU 4

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## CEVAP 4

Not: "*" simgesi o ana kadar sıraldığımız verilerin sonuna koyulmuştur.

Birinci Adım : 2 ve 7 yer değiştirir.
[2*,3,5,8,7,9,4,15,6]

Birinci Adım : 3 halihazırda sıralı olduğu için değişikliğe gerek yok.

Üçüncü Adım : 4 ve 5 yer değiştirir.
[2,3,4*,8,7,9,5,15,6]

Dördüncü Adım : 5 ve 8 yer değiştirir.
[2,3,4,5*,7,9,8,15,6]
