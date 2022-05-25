## Project 1

## Insertion Sort Project

## [22,27,16,2,18,6] -> Insertion Sort

1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.


* Dizideki ilk eleman diğer elemanlarla karşılatırılır ve dizinin en küçük elemanı ilk elemanla yer değiştirir.
* Dizi [2,27,16,22,18,6] olur.

* Dizideki ikinci eleman sağındaki elemanlarla karşılatırılır ve dizinin en küçük elemanı ikinci elemanla yer değiştirir.

* Dizi [2,6,16,22,18,27] olur.

* Dizideki üçüncü eleman sağındaki elemanlarla karşılatırılır ve dizinin en küçük elemanı üçüncü elemanla yer değiştirir.

* Dizi [2,6,16,22,18,27] olur.

* Dizideki dördüncü eleman sağındaki elemanlarla karşılatırılır ve dizinin en küçük elemanı üçüncü elemanla yer değiştirir.
* Dizi [2,6,16,18,22,27] olur.

2- Big-O gösterimini yazınız.


* Insertion Sort algoritması sıralama yaparken her aşamada baz aldığı elemanı sağındaki bütün elemanlarla kıyaslıyor.


* n tane elemanı olan bir dizide ilk aşamada n kere işlem yapıyor. ikinci aşamada n-1 tane ve dizide bir eleman kalana kadar bu işlem böyle devam ediyor.

* Big-O Notation için n + (n-1) + (n-2)... + (n-(n-1) şeklinde toplanıyor ve bu durum n ardışık sayının toplamı formülünden n * (n+1) / 2 bu formülü açtığımınzda (n^2 + 2n + 1) / 2 gelir bu formülde baskın olan n^2 olduğu için Big-o Notation n^2 oluyor.

3- Time Complexity: 

* Average case: Aradığımız sayının ortada olması

* Worst case: Aradığımız sayının sonda olması

* Best case: Aradığımız sayının dizinin en başında olması.

4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

* Dizide 18 sayısı ortada bulunmaktadır. Bu yüzden average case kapsamına girmektedir.

5- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

* 1. aşama (9 işlem) = [2,3,5,8,7,9,4,15,6]
* 2. aşama (8 işlem) = [2,3,5,8,7,9,4,15,6]
* 3. aşama (7 işlem) = [2,3,4,8,7,9,5,15,6]
* 4. aşama (6 işlem) = [2,3,4,5,7,9,8,15,6]
* 5. aşama (5 işlem) = [2,3,4,5,6,9,8,15,7]
* 6. aşama (4 işlem) = [2,3,4,5,6,7,8,15,9]
* 7. aşama (3 işlem) = [2,3,4,5,6,7,8,15,9]
* 8. aşama (2 işlem) = [2,3,4,5,6,7,8,9,15]








## Project 2

## Merge Sort Project

## [16,21,11,8,12,22] -> Merge Sort

1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

* Dizide verilen elemanlar iki parçaya bölünür. Her eleman tek kalana kadar.
* İlk aşama= [16,21,11] ve [8,12,22]
* İkinci aşama = [16,21], [11], [8,12] ve [22]
* Üçüncü aşama = [16], [21], [11], [8], [12] ve [22]
* Her eleman tek kaldıktan sonra sayılar sıralı olacak şekilde tekrar birleştirilir.
* Dördüncü aşama = [16,21], [11], [8,12] ve [22]
* Beşinci aşama = [11,16,21] ve [8,12,22]
* Altıncı aşama = [8,11,12,16,21,22]

2- Big-O gösterimini yazınız.

* Merge Sort algoritması uygulanmasında dizi n/2 kere bölünmek için ve n/2 kere de birleştirilmek için işlem görür.

* 2^x = n ve x = logn oluyor. Bölme ve birleştirme yaparak n işlem yapıyoruz ve bu durumda Big-O Notationumuz O(nlogn) olarak ortaya çıkıyor.









## Project 3

## Binary Search Tree Project

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary-Search-Tree

1- Yukarıdaki dizinin Binary-Search-Tree aşamalarını yazınız.

* Root = 4
* -------------4---------------

  -------2-----------7---------

  --1-----3-----5--------8-----

  0-----------------6---------9

