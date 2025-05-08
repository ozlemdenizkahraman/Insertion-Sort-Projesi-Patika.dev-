1. [22, 27, 16, 2, 18, 6] Dizisinin Insertion Sort Aşamaları
Insertion Sort Mantığı:
Her adımda bir eleman alınır ve uygun yere yerleştirilir.
İlk eleman zaten sıralı kabul edilir, sonraki elemanlar uygun yerlere kaydırılarak eklenir.
Adımlar:

Başlangıç: [22, 27, 16, 2, 18, 6]
22 zaten sıralı kabul edilir.

Sıradakine bakılır:
27 > 22 → Yerinde kalır.
Dizi: [22, 27, 16, 2, 18, 6]

Sıradakine bakılır:
16 < 27 → 27 sağa kayar.
16 < 22 → 22 sağa kayar.
16 başa yerleşir.
Dizi: [16, 22, 27, 2, 18, 6]

Sıradakine bakılır:
2 < 27 → 27 kayar.
2 < 22 → 22 kayar.
2 < 16 → 16 kayar.
2 en başa yerleşir.
Dizi: [2, 16, 22, 27, 18, 6]

Sıradakine bakılır:
18 < 27 → 27 kayar.
18 < 22 → 22 kayar.
18 > 16 → 16'nın sağına yerleşir.
Dizi: [2, 16, 18, 22, 27, 6]

Sıradakine bakılır:
6 < 27 → 27 kayar.
6 < 22 → 22 kayar.
6 < 18 → 18 kayar.
6 < 16 → 16 kayar.
6 > 2 → 2'nin sağına yerleşir.
Son Dizi: [2, 6, 16, 18, 22, 27]

Big-O Gösterimi:
Worst Case: O(n**2) (Ters sıralı dizi)
Average Case: O(n**2)
Best Case: O(n)  (Zaten sıralı dizi)

Time Complexity & 18 Sayısının Durumu:
Sıralanmış Dizi: [2, 6, 16, 18, 22, 27]
18 sayısı ortada olduğu için → Average Case kapsamına girer.
......

2. [7, 3, 5, 8, 2, 9, 4, 15, 6] Dizisinin Selection Sort İlk 4 Adımı
Selection Sort Mantığı:
Her adımda en küçük eleman bulunur ve baştaki uygun yere yerleştirilir.

1. Adım:
Tüm dizide en küçük sayı 2 (4. indeks).
2 ile 7 yer değiştirir.
Dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]

2. Adım:
Kalan dizi [3, 5, 8, 7, 9, 4, 15, 6]
En küçük 3 zaten başta → Değişiklik yok.
Dizi: [2, 3, 5, 8, 7, 9, 4, 15, 6]

3. Adım:
Kalan dizi [5, 8, 7, 9, 4, 15, 6]
En küçük 4 (5. indeks).
4 ile 5 yer değiştirir.
Dizi: [2, 3, 4, 8, 7, 9, 5, 15, 6]

4. Adım:
Kalan dizi [8, 7, 9, 5, 15, 6]
En küçük 5 (3. indeks).
5 ile 8 yer değiştirir.
Dizi: [2, 3, 4, 5, 7, 9, 8, 15, 6]

İlk 4 Adım Sonucu:
[2, 3, 4, 5, 7, 9, 8, 15, 6]

Devam edilseydi bir sonraki en küçük 6 olacaktı.
