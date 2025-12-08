[22, 27, 16, 2, 18, 6] → Insertion Sort
Insertion Sort Adımları

Başlangıç dizi:
[22, 27, 16, 2, 18, 6]

1. adım: (27, 22’den büyük → yer değişmez)
[22, 27, 16, 2, 18, 6]

2. adım: (16 alınır; 27 ve 22’den küçüktür → sola kaydırılır)
[16, 22, 27, 2, 18, 6]

3. adım: (2 alınır; tüm elemanlardan küçüktür → en başa gelir)
[2, 16, 22, 27, 18, 6]

4. adım: (18 alınır; 27 ve 22’den küçüktür → araya yerleşir)
[2, 16, 18, 22, 27, 6]

5. adım: (6 alınır; hepsinden küçüktür → başa kadar kaydırılır)
[2, 6, 16, 18, 22, 27]

Son sıralanmış dizi:
 [2, 6, 16, 18, 22, 27]
//////////////////////////////////////////////////
/////////////////////////////////////////////////
Big-O Gösterimi

Insertion Sort’un en kötü durumda çalışma süresi:
O(n²)

//////////////////////////////////////////////////
/////////////////////////////////////////////////

Time Complexity — 18 sayısı hangi case kapsamındadır?

Sıralı dizi:
[2, 6, 16, 18, 22, 27]

18 dizinin ortasında yer almaktadır.

 18 → Average Case
 //////////////////////////////////////////////////
/////////////////////////////////////////////////

[7,3,5,8,2,9,4,15,6] → Selection Sort İlk 4 Adım

Başlangıç dizi:
[7, 3, 5, 8, 2, 9, 4, 15, 6]

1. adım: (En küçük: 2 → 7 ile yer değiştirir)

[2, 3, 5, 8, 7, 9, 4, 15, 6]

2. adım: (Kalanlardan en küçük: 3 → zaten doğru yerde)

[2, 3, 5, 8, 7, 9, 4, 15, 6]

3. adım: (Kalanlardan en küçük: 4 → 5 ile yer değiştirir)

[2, 3, 4, 8, 7, 9, 5, 15, 6]

4. adım: (Kalanlardan en küçük: 5 → 8 ile yer değiştirir)

[2, 3, 4, 5, 7, 9, 8, 15, 6]
 
