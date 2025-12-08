[22, 27, 16, 2, 18, 6] → Ekleme Sıralama

Ekleme Sıralama Adımları

Başlangıç ​​dizisi: [22, 27, 16, 2, 18, 6]

adım: (27, 22'den büyük → yer değişmez)  
[22, 27, 16, 2, 18, 6]

adım: (16 alınır; 27 ve 22'den → sola kaydırılır)  
[16, 22, 27, 2, 18, 6]

adım: (2 alınır; tüm elemanlardan resimler → en başa gelir)  
[2, 16, 22, 27, 18, 6]

: (18 adım alınır; 27 ve 22'den boyutlarda → araya yerleşir)  
[2, 16, 18, 22, 27, 6]

adım: (6 alınır; bebeklerin boyutları → başa kadar kaydırılır)  
[2, 6, 16, 18, 22, 27]

Son sıralanmış dizi:  
[2, 6, 16, 18, 22, 27]

//////////////////////////////////////////////// ////////////////////////////////////////////////

Big-O Gösterimi

Insertion Sort'un en kötü durumda çalışma süresi: **O(n²)**

/////////////////////////////////////////////////// //////////////////////////////////////////////////////////////

Zaman Karmaşıklığı — 18 adet hangi durum kapsamındadır?

Sıralı dizi: [2, 6, 16, 18, 22, 27]

18 dizinin ortasında yer almaktadır.

18 → **Ortalama Durum**

//////////////////////////////////////////////// //////////////////////////////////////////////////////////////

[7,3,5,8,2,9,4,15,6] → Seçmeli Sıralama İlk 4 Adım

Başlangıç ​​dizisi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

adım: (En küçük: 2 → 7 ile yer değiştirir)  
[2, 3, 5, 8, 7, 9, 4, 15, 6]

adım: (Kalanlardan en küçük: 3 → zaten doğru yerde)  
[2, 3, 5, 8, 7, 9, 4, 15, 6]

(Kalanlardan en küçük: 4 → 5 ile yer adım değişiklikleri)  
[2, 3, 4, 8, 7, 9, 5, 15, 6]

(Kalanlardan en küçük: 5 → 8 ile yer adım değişiklikleri)  
[2, 3, 4, 5, 7, 9, 8, 15, 6]
