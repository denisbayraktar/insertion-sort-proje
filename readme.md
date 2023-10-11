Insertion Sort Proje

[22,27,16,2,18,6] -> Insertion Sort
Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

1. aşama: En küçük değer en başa alınır. Fakat en baştaki sayısının soluna alınmaz, en baştaki sayısı ile yer değiştirilir.
[2,27,16,22,18,6]

2. aşama: 2 sayısı sabit tutulur. En küçük değer 2'den sonra gelen sayı ile yer değiştirilir.
[2,6,16,22,18,27]

3. aşama: 16 sayısı en küçük üçüncü sayı olduğundan yer değiştirilmez.
[2,6,16,22,18,27]

4. aşama: 2, 6 ve 16 sayısı sabit tutulur. Kalan 3 sayı içinden en küçük sayı olan 18 ile 22 yer değişir.
[2,6,16,18,22,27]

5. aşama: İstenen sıralama elde edildiğinden yer değiştirme işlemi sonlanır.
[2,6,16,18,22,27]


Big-O gösterimini yazınız.
Worst Case: O(n²) = n+(n-1)+(n-2)....+1


Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

1. Average case: Aradığımız sayının ortada olması
2. Worst case: Aradığımız sayının sonda olması
3. Best case: Aradığımız sayının dizinin en başında olması.

Dizi küçükten büyüğe sıralandığında 18 sayısının 4. sayı olduğu görülür. Yani ortada bir değer olarak görebilir ve average case diyebiliriz.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. [2,3,5,8,7,9,4,15,6] En küçük sayı 2 ile 7 yer değiştirdi.
2. [2,3,4,8,7,9,5,15,6] 3 sıralamada doğru yerde olduğundan, 4 ile 5 yer değiştirdi.
3. [2,3,4,5,7,9,8,15,6] 5 ile 8 yer değiştirdi.
4. [2,3,4,5,6,9,8,15,7] 6 ile 7 yer değiştirdi.
 
