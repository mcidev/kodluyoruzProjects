# Insertion Sort Projesi
Proje İçeriği:
```
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.
3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```

Proje 1 Cevaplar:
---
*1. Dizinin Insertion Sort algortitmasına göre çözüm adımları:* 
```
1 -> [22,27,16,2,18,6]
2 -> [2,27,16,22,18,6]
3 -> [2,6,16,22,18,27]
4 -> [2,6,16,18,22,27]
```
*2. Dizinin Big-O gösterimi:*

```
O(n^2)
```

*3. Time Complexity*
```
Worst Case: İfade "Linear Search" için kullanılsaydı doğru olurdu.
Best Case: İfade "Linear Search" için kullanılsaydı doğru olurdu.
Avarage Case: Aradığımız sayının dizinin ortasında olması değil; algoritmanın kullanılırken karşılacağı dizilerin gerçek hayattaki
sıralanma senaryolarının oransal bir ifadesi olarak düşünülebilir.

```
*4. Dizi sıralandıktan sonra 18 sayısının kapsamı:*

```
Dizi sıralandıktan sonra 18 sayısı herhangi bir kapsama girmez çünkü hali hazırda sıralanmış bir dizi için "İnsertion Sort" 
algoritması işlevini yerine getirmiş demektir. Herhangi bir "Search" algoritması kapsamında olsa bir değerlendirme yapılabilirdi.
```

*[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız:*
```
1 -> [2,3,5,8,7,9,4,15,6]
2 -> [2,3,4,8,7,9,5,15,6]
3 -> [2,3,4,5,7,9,8,15,6]
4 -> [2,3,4,5,6,9,8,15,7]
