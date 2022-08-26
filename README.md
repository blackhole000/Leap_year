# Leap_year.py  (Artık yıl bulma)

## Artık yıl Nedir)
Artık yıl, bir yılın 366 gün sürdüğü yıllara denir.
Daha fazal bilgi için [Wikipedia](https://tr.wikipedia.org/wiki/Art%C4%B1k_y%C4%B1l) - Wikipedia Artık Yıl sayfasını inceleyiniz.
# Nasıl Hesaplanır?
Yılın artık yıl olması için ön koşul o yıl 4'e tam bölünebilmesi gerekmektir. Ancak sadece bu yeterli değildir. Bilimsel sebeplerden dolayı 100 bölünmeyip 400 tam bölünebilen yıllar artık yıl olarak kabul edlir.

### Psodo Code

1. Yıl 4 ile eşit bölünebilir ise, adım 2'e gidin. Aksi durumda, 5. adıma gidin.
2. Yıl 100 ile eşit bölünebilir ise, adım 3'e gidin. Aksi durumda, 4. adıma gidin.
3. Yıl 400 ile eşit bölünebilir ise, adım 4'e gidin. Aksi durumda, 5. adıma gidin.
4. Yıl artık yıldır (366 gün vardır).
5. Yıl artık yıl değildir (365 gün vardır)

### Flowchart

![indir](https://user-images.githubusercontent.com/74445249/186960314-543de1ed-3a6b-4445-a0f8-7dc79434a428.png)


### Kolay mı zor mu?
Kod yazılırken iç içe(nested) if - else yapısı ile yazıldığı için başlangıç seviye bir koddur. 

Herkese iyi çalışmalar dilerim.
