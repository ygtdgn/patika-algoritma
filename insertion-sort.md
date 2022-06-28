# Insertion Sort Projesi
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[2,27,16,22,18,6] --> 2 ile 22 yer değiştirir.
[2,6,16,22,18,27] --> 6 ile 27 yer değiştirir.
[2,6,16,22,18,27] --> Üç sayı sıralı olduğu için yer değiştirmez.
[2,6,16,18,22,27] --> 18 ile 22 yer değiştirir.
[2,6,16,18,22,27] --> 6. eleman yer değiştirmez dizi sıralıdır.

2. Big-O gösterimini yazınız.
Kural n(n+1)/2 'dir. Buradan Big-O Notation'umuz O(n^2) olur yani O(6^2) yani O(32) olmuş olur.

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
  Average Case: 16, 18
  Worst Case: 27
  Best Case: 2


4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

  Average Case
  
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]
