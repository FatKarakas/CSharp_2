Plaka Kodu → Şehir Adı Uygulaması (Enum Kullanımı):
Bu proje, C# Windows Forms kullanılarak geliştirilmiş basit bir uygulamadır.
Kullanıcıdan alınan plaka kodu, enum yapısı kullanılarak şehir adına dönüştürülür ve ekranda gösterilir.

Kullanılan Teknolojiler:
C#
.NET Framework
Windows Forms
Visual Studio


Projenin Amacı:
Bu uygulamanın amacı;
enum yapısının Windows Forms içinde nasıl kullanıldığını göstermek
Sayısal bir değeri (plaka) anlamlı bir metne (şehir adı) dönüştürmek
Enum casting ((enum)int) mantığını öğretmek

X elemanı, enum index’ini plaka numaralarıyla uyumlu yapmak için eklenmiştir.

Uygulama Nasıl Çalışır?
Kullanıcı TextBox içine plaka kodunu girer
Butona tıklanır
Girilen sayı enum’a dönüştürülür
Karşılık gelen şehir adı Label üzerinde gösterilir

Dikkat Edilmesi Gerekenler:
Geçersiz plaka girilirse uygulama hata verebilir
Giriş kontrolü (try-catch) eklenmesi önerilir
Enum dışı değerler için kontrol yapılmalıdır

Geliştirme Önerileri:
try-catch ile hata kontrolü eklenebilir
Türkiye’deki tüm plakalar eklenebilir
ComboBox + enum kullanımı yapılabilir
Kullanıcıya uyarı mesajları gösterilebilir
