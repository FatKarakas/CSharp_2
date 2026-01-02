Rastgele Sayı Tahmin Oyunu:
Bu proje, C# Windows Forms kullanılarak geliştirilmiş basit bir sayı tahmin oyunudur.
Kullanıcı, 1 ile 4 arasında tahmin ettiği sayıları TextBox’lara girer. Butona basıldığında sistem rastgele sayılar üretir ve tahminlerin doğruluğunu renkle gösterir.

 Kullanılan Teknolojiler:
C#
.NET Framework
Windows Forms
Visual Studio

Uygulama Nasıl Çalışır?
Kullanıcı 4 adet TextBox içerisine 1–4 arasında sayı girer.
Son TextBox doldurulduğunda Buton görünür olur.
Butona basıldığında:
Sistem rastgele 4 adet sayı üretir.
Bu sayılar Label’larda gösterilir.
Karşılaştırma yapılır:
Doğru tahmin → Yeşil 
Yanlış tahmin → Kırmızı

Kurallar:
Girilen değerler 1 ile 4 arasında olmalıdır.
Karşılaştırma string üzerinden yapılmaktadır.
Her buton tıklamasında yeni rastgele sayılar üretilir.

Kod Mantığı (Özet)
Random sınıfı ile sayı üretimi
TextBox.Text ve Label.Text karşılaştırması
Doğru/yanlış durumuna göre BackColor değiştirme
TextChanged eventi ile buton kontrolü
