# Bag Stock Management (Desktop)

Bir çanta firması için geliştirilmiş masaüstü ürün, stok ve personel takip uygulaması. C# Windows Forms ile yazılmıştır ve SQL Server kullanır.

## Teknolojiler

- C#, .NET Framework 4.7.2
- Windows Forms
- SQL Server (ADO.NET)

## Özellikler

- Kullanıcı girişi
- Ürün kontrol ekranı: ürünleri listeleme ve inceleme
- Ürün güncelleme ekranı: ürün bilgisi ve stok düzenleme
- Personel yönetimi: yalnızca yönetici erişebilir

## Kurulum

Gereksinimler: Windows, Visual Studio 2019 veya üzeri, SQL Server (Express yeterli).

1. Repoyu klonlayın ve `CantaBılgı/CantaBılgı.sln` dosyasını Visual Studio ile açın.
2. SQL Server'da `CantaStokYonetimi` adlı bir veritabanı oluşturun. `Personel` ve `Urunler` tabloları gereklidir.
3. `CantaBılgı/App.config` içindeki `CantaStokYonetimiConnectionString` değerindeki `Data Source` alanını kendi SQL Server örneğinizle değiştirin.
4. Projeyi derleyip çalıştırın (F5).

## Ekran Görüntüleri

<img src="https://raw.githubusercontent.com/ahmetalpcinar/ahmetalpcinar/main/PNG/Images/imageBSIF1.png" alt="Giriş" width="420"> <img src="https://raw.githubusercontent.com/ahmetalpcinar/ahmetalpcinar/main/PNG/Images/imageBSIF2.png" alt="Ana sayfa" width="420">
<img src="https://raw.githubusercontent.com/ahmetalpcinar/ahmetalpcinar/main/PNG/Images/imageBSIF4.png" alt="Ürün kontrol" width="420"> <img src="https://raw.githubusercontent.com/ahmetalpcinar/ahmetalpcinar/main/PNG/Images/imageBSIF5.png" alt="Ürün güncelleme" width="420">
<img src="https://raw.githubusercontent.com/ahmetalpcinar/ahmetalpcinar/main/PNG/Images/imageBSIF3.png" alt="Personel kontrol" width="420">
