Ödevin Amacı
Bu ödevin amacı, Windows Forms uygulaması kullanarak çok formlu bir yapı yerine eğlenceli ve işlevsel bir sayı tahmin oyunu geliştirmektir. Oyun, kullanıcının 3, 4 veya 5 haneli rastgele üretilen bir sayıyı (rakamlar tekrarlanmadan) tahmin etmesini sağlar. Tahmin doğruluğu yeşil (doğru yer), sarı (yanlış yer), kırmızı (yok) renk kodlarıyla belirtilir. Klavyesiz cihazlar için ekranda rakam butonları eklenmiş, kullanıcı girişi ve skor takibi veritabanı ile sağlanmıştır.

Ödev tek başıma geliştirilmiştir.


Proje, Visual Studio’da C# Windows Forms App olarak oluşturulmuştur. Ana özellikler şu şekilde gerçekleştirilmiştir:

Kullanıcı girişi ve yeni kullanıcı kaydı için login ve register formları tasarlandı.
Kullanıcı bilgileri (ad, soyad, telefon, e-posta) veritabanına kaydedildi.
Rastgele sayı üretimi tekrarlanmayan rakamlarla yapıldı.
Klavyesiz kullanım için 0-9 rakam butonları ve sil butonu eklendi.
Tahmin sonrası ipuçları renk kodlarıyla (yeşil, sarı, kırmızı) görüntülendi.
Puan bilgileri veritabanına kaydedildi.
En yüksek 5 skor ana formda sağ üst köşede ListBox ile listelendi.
Veritabanı işlemleri için System.Data.SQLite kütüphanesi kullanıldı.

Proje geliştirilirken temiz kod ve kullanıcı dostu arayüz ön planda tutuldu.
