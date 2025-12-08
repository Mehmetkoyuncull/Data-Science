[22, 27, 16, 2, 18, 6] → Insertion Sort

Insertion Sort Adımları

Başlangıç dizisi: [22, 27, 16, 2, 18, 6]

Step: (27, 22'den büyük → yer değişmez)  
[22, 27, 16, 2, 18, 6]

Step: (16 alınır; 27 ve 22'den küçük olduğu için sola kaydırılır)  
[16, 22, 27, 2, 18, 6]

Step: (2 alınır; tüm elemanlardan küçük → en başa alınır)  
[2, 16, 22, 27, 18, 6]

Step: (18 alınır; 27 ve 22'den küçük → araya yerleşir)  
[2, 16, 18, 22, 27, 6]

Step: (6 alınır; birçok elemandan küçük → başa doğru kaydırılır)  
[2, 6, 16, 18, 22, 27]

Son sıralanmış dizi:  
[2, 6, 16, 18, 22, 27]

//////////////////////////////////////////////// ////////////////////////////////////////////////

Big-O Gösterimi

Insertion Sort için en kötü durum zaman karmaşıklığı: **O(n²)**

/////////////////////////////////////////////////// //////////////////////////////////////////////////////////////

Zaman Karmaşıklığı — 18 sayısı hangi Case kapsamındadır?

Sıralı dizi: [2, 6, 16, 18, 22, 27]

18 dizinin ortasında bulunduğu için:

18 → **Average Case**

//////////////////////////////////////////////// //////////////////////////////////////////////////////////////

[7,3,5,8,2,9,4,15,6] → Selection Sort İlk 4 Step

Başlangıç dizisi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

Step: (En küçük: 2 → 7 ile yer değiştirir)  
[2, 3, 5, 8, 7, 9, 4, 15, 6]

Step: (Kalan elemanlar içinde en küçük: 3 → zaten doğru yerde)  
[2, 3, 5, 8, 7, 9, 4, 15, 6]

Step: (Kalan elemanlar içinde en küçük: 4 → 5 ile yer değiştirir)  
[2, 3, 4, 8, 7, 9, 5, 15, 6]

Step: (Kalan elemanlar içinde en küçük: 5 → 8 ile yer değiştirir)  
[2, 3, 4, 5, 7, 9, 8, 15, 6]
