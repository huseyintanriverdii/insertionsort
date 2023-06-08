# insertionsort
Veri Yapıları ve Algoritmalar Proje 1

[22,27,16,2,18,5]  n
22[27,16,2,18,6]   n-1
22,27[16,2,18,6]   n-2
16,22,27[2,18,6]   n-3
2,16,22,27[18,6]   n-4
2,16,18,22,27,[6]  n-5
2,6,16,18,22,27    1

BIG-O gösterimi n*(n+1)/2=n^2

18 sayısı hangi case kapsamına girer?
Average case: Aradığımız sayının ortada olması

[7,3,5,8,2,9,4,15,6]
[2,3,4,8,7,9,5,15,6] 1.adım
[2,3,4,5,7,9,8,15,6] 2.adım
[2,3,4,5,6,9,8,15,7] 3.adım
[2,3,4,5,6,7,8,15,9] 4.adım
[2,3,4,5,6,7,8,9,15] 5.adım
