# Kelime Tahmin Oyunu

Bu, Python ile yazılmış basit bir kelime tahmin oyunudur. Oyuncudan rastgele seçilen bir kelimeyi birer harf tahmin ederek bulması istenir. Oyun, doğru ve yanlış tahminler için geri bildirim sağlar ve sınırlı sayıda deneme hakkı sunar.

## Nasıl Oynanır

1. Oyun, önceden tanımlanmış bir listeden rastgele bir kelime seçer.
2. Oyuncuya, bilinmeyen harfler için alt çizgiler (`_`) gösterilir.
3. Oyuncu, her seferinde bir harf tahmin eder.
4. Eğer tahmin edilen harf kelimenin içinde varsa, doğru pozisyonlarda gösterilir.
5. Eğer tahmin edilen harf kelimenin içinde yoksa, oyuncu bir hakkını kaybeder.
6. Oyun şu durumlarda sona erer:
   - Oyuncu kelimenin tamamını doğru tahmin ederse.
   - Oyuncunun tahmin hakkı biterse.

## Özellikler

- Önceden tanımlanmış bir listeden rastgele kelime seçer.
- Oyuncunun doğru ve yanlış tahminlerini takip eder.
- Her tahminden sonra geri bildirim sağlar.
- Sınırlı sayıda yanlış tahmin hakkı (varsayılan: 6).

## Gereksinimler

- Python 3.6 veya üstü.

## Nasıl Çalıştırılır

1. Depoyu klonlayın veya indirin.
2. Terminali açın ve script'in bulunduğu dizine gidin.
3. Oyunu aşağıdaki komutla çalıştırın:

   ```bash
   python word_guess_game.py
   ```

## Örnek Oyun Akışı

```
Kelime Tahmin Oyununa Hoş Geldiniz!
Kelimeyi birer harf tahmin ederek bulun.
Yanlış tahmin hakkınız: 6
______
Bir harf girin: p
Doğru tahmin!
p_____
Bir harf girin: y
Doğru tahmin!
py____
Bir harf girin: z
Yanlış tahmin! Kalan hakkınız: 5
py____
...
```
