Sürüklenebilir Buton Uygulaması:
Bu proje, C# Windows Forms kullanılarak geliştirilmiş basit bir masaüstü uygulamasıdır.
Uygulamada yer alan bir buton, fare ile tıklanıp sürüklenerek form üzerinde hareket ettirilebilir.
Butonun anlık X ve Y koordinatları ekranda gösterilir.

Projenin Amacı:
Mouse event’lerini (MouseDown, MouseMove, MouseUp) uygulamalı öğrenmek
WinForms kontrollerinin konumlarını dinamik olarak değiştirmek
Kullanıcı etkileşimini (drag & drop mantığı) kavramak

Kullanılan Yapılar:
MouseDown → Sürükleme başlatılır
MouseMove → Fare hareketine göre buton konumu güncellenir
MouseUp → Sürükleme işlemi sonlandırılır
Left / Top → Butonun ekrandaki konumu
Label → X ve Y koordinatlarını göstermek için

Kullanılan Teknolojiler:
C#
.NET Framework
Windows Forms (WinForms)
Visual Studio

Uygulama Nasıl Çalışır?
Kullanıcı butona fare ile basılı tutar
Fare hareket ettikçe buton form üzerinde sürüklenir
Butonun güncel X ve Y koordinatları label’larda gösterilir
Fare bırakıldığında sürükleme işlemi sona erer

Geliştirilebilir Özellikler:
Birden fazla sürüklenebilir kontrol eklenmesi
Form sınırları dışına çıkmayı engelleme
Gerçek zamanlı koordinat paneli
Sürükleme sırasında görsel geri bildirim
