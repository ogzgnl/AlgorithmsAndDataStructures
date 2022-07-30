#  Proje 1
[22,27,16,2,18,6] -> Insertion Sort

* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.
* Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
* Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


###  [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
--------------------

# Cevaplar
- Bir tur bütün verileri gezip en küçük değeri bulacağız sonrasında en küçük ile birinci değerin yeri değişecek
- Bu sayede bütün liste sıralanmış olacak.
- Big O = ON^2 iki adet n kadar işlem yapan bir loop var N*N= N square
- Time Complexity:
- Best: 0(n) - Eğer liste sıralı ise yine bir tam tur atacak.
- Average, Worst: o(n^2) - Liste hiç sıralı değilse iki loop'u da tam dönecektir. Average case için bazı elemanlar sıralı ise daha hızlı biter ama o(n^2) daha sağlıklı olur.
- 18 Sayısı muhtemelen average case kapsamına girer çünkü dördüncü looptan sonra listeye eklenecektir.

---
#####  [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
* 2-3-5-8-7-9-4-15-6
* 2-3-4-8-7-9-5-15-6
* 2-3-4-5-6-9-5-15-7
* 2-3-4-5-6-7-5-15-9

ilk 4 adım bitmiştir.
