# Sayi_Basamaklarini_Ayristirma_C_Programlama
***Sayı Basamaklarını Ayrıştırma (C Programlama)***
Bu basit C programı, kullanıcıdan alınan maksimum 6 basamaklı (yüz binler basamağına kadar) bir tam sayıyı basamaklarına ayırır ve her bir basamağı ekrana alt alta yazdırır.

***Özellikler***
Sınır Kontrolü: switch-case yapısı kullanılarak 6 basamaktan büyük sayıların girilmesi engellenir.

Matematiksel Mantık: Sayıları ayırmak için tam sayı bölmesi (/) ve mod alma (%) operatörleri kullanılır.

Temiz Çıktı: Her basamak sırasıyla (Yüz binler, On binler, Binler, Yüzler, Onlar, Birler) ekrana basılır.

***Nasıl Çalışır?***
Programın temel mantığı şu iki operatöre dayanır:

Bölme (/): Sayıyı küçülterek hedef basamağı "birler basamağı" konumuna getirir.

Mod (%): Bir sayının 10'a bölümünden kalanı bularak o anki en sağdaki basamağı yakalar.

Örnek Hesaplama:
Sayımız 123456 olsun.

yuzbinler = 123456 / 100000 → Sonuç: 1

onbinler = (123456 / 10000) % 10 → 12 % 10 → Sonuç: 2

***Kurulum ve Çalıştırma***
Bilgisayarınızda bir C derleyicisinin (GCC, Clang, MSVC vb.) kurulu olduğundan emin olun.

Dosyayı indirin veya kopyalayın: main.c

Terminal veya komut satırını açıp şu komutu çalıştırın:

Bash
gcc main.c -o basamak_ayirici
./basamak_ayirici
***Örnek Çıktı:***
***Plaintext:***
bir sayi giriniz: 543210
5
4
3
2
1
0
