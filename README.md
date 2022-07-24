# Patika.dev-Insertion-Sort-Projesi
**[22,27,16,2,18,6]**  -> Insertion Sort

1.  Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2.  Big-O gösterimini yazınız.
3.  Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.  Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
# Insertion Sort Aşamaları
> İlk aşama

 - [ 22| ,27,16,2,18,6 ]

> İkinci aşama

 - [ 22,27| ,16,2,18,6 ]

> Üçüncü aşama

 - [ 22,16,27| ,2,18,6 ]
 - [ 16,22,27| ,2,18,6 ]

>  Dördüncü aşama

 - [ 16,22,2,27| ,18,6 ]
 - [ 16,2,22,27| ,18,6 ]
 - [ 2,16,22,27| ,18,6 ]
 

> Beşinci aşama

 - [ 2,16,22,18,27| ,6 ]
 - [ 2,16,18,22,27| ,6 ]
 

> Altıncı aşama

 - [ 2,16,18,22,6,27| ]
 - [ 2,16,18,6,22,27| ]
 - [ 2,16,6,18,22,27| ]
 - **[ 2,6,16,18,22,27 ]**
 

## Big O Notation Gösterimi

Worst Case   : O (n²)

Average Case : O (n²)

Best Case    : O (n)

## Time Complexity
Worst Case: [ 27,22,18,16,6,2 ] -> O (n²)


Best Case: [ 2,6,16,18,22,27 ] -> O (n)

## Dizideki 18 sayısının Case Durumu
[ 2,6,16,**18**,22,27 ]

18 sayısı Average Case kapsamına girer.

## [ 7,3,5,8,2,9,4,15,6 ] dizisinin Insertion Sort'a göre ilk 4 adımı

 1. [ 7| ,3,5,8,2,9,4,15,6 ]
 2. [ 3,7| ,5,8,2,9,4,15,6 ]
 3. [ 3,5,7| ,8,2,9,4,15,6 ]
 4. [ 3,5,7,8| ,2,9,4,15,6 ]

www.patika.dev
