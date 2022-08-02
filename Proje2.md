## Proje 2
[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
-----
# Cevaplar
-[16,21,11,8,12,22] Parçalamadan önce
-[16,21,11],[8,12,22] İkiye ayırdık
- [16,21] [11]  [8,12]  [22] Tekrar ikiye ayırdık
- Burada hespini bir bir ayırıp önceki bloklara sıralı bir şekilde yazdık. Tek olanlara ellemedik
- [11,16,21]   [8-12-22] Burada artık iki grupta sıralı olduğu için direkt olarak soldaki kümenini birincisi ile sağdakini karşılaştırdık. Sonrasında böyle devam etti
- [8-11-12-16-21-22] Sonunda bu sonucu elde ettik.

# Big O:
n log (n)
