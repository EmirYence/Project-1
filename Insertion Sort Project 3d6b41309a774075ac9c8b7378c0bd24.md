# Insertion Sort Project

[22, 27, 16, 2, 18, 6] > Insertion Sort

A. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

1.  [**22, 27**, 16, 2,18, 6] .... 1
2.  [**16, 22, 27**, 2,18, 6]
3.  [**2, 16, 22, 27**,18, 6]
4.  [**2, 16, 18, 22, 27**, 6] .... n-1
5.  [**2, 6, 16, 18, 22, 27**] .... n

! Yukarıda verilen dizinin ‘’Selection Sort’’ türüne göre yazımı da bu şekilde,

1. [**22**,27,16,2,18,6]
2. [2,**27**,16,22,18,6]
3. [2,6,**16**,22,18,27]
4. [2,6,16,**22**,18,27]
5. [2,6,16,18,**22**,27]
6. [2,6,16,18,22,**27**]

B. Yukarıda verilen dizinin Big-O gösterimini yazınız,

Worst case…  n!= n*(n+1)/2= (n^2+n)/2 => **O(n^2)** 

C. Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

D. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız,

- Dizinin ortasında olduğu için ‘’18’’ sayısı Average case kapsamındadır.

**[7,3,5,8,2,9,4,15,6**] 

E. dizisinin Insertion Sort türüne göre ilk ‘’4’’adımını yazınız,

1. [**3,7**,5,8,2,9,4,15,6]
2. [**3,5,7**,8,2,9,4,15,6]
3. [**3,5,7,8**,2,9,4,15,6]
4. [**3,5,7,2,8**,9,4,15,6]…


